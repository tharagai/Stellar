<script context="module">
	export function preload({ params, query }) {
		return this.fetch(`blog.json`).then(r => r.json()).then(posts => {
			return { posts };
		});
	}
</script>

<script>
	export let posts;
</script>

<style>
	ul {
		margin: 0 0 1em 0;
		line-height: 1.5;
	}
</style>

<svelte:head>
	<title>Blog</title>
</svelte:head>

<section class="js-parallax u-promo-block u-promo-block--mheight-500 u-overlay u-overlay--dark text-white" style="background-image: url(&quot;assets/img-temp/1920x1080/img6.jpg&quot;); background-position: 50% 0px;">
	<!-- Promo Content -->
	<div class="container u-overlay__inner u-ver-center u-content-space">
	  <div class="row justify-content-center">
		<div class="col-12">
		  <div class="text-left">
			<h1 class="display-sm-4 display-lg-3 u-letter-spacing-sm">Specialists
				that deliver</h1>
			<p class="h6   mb-0">We know the process, and empower a multidisciplinary team to collaborate with you and deliver delightful solutions.</p>
		  </div>
		</div>
	  </div>
	</div>
	<!-- End Promo Content -->
  </section>
<ul>
	{#each posts as post}
		<!-- we're using the non-standard `rel=prefetch` attribute to
				tell Sapper to load the data for the page as soon as
				the user hovers over the link or taps it, instead of
				waiting for the 'click' event -->
		<li><a rel='prefetch' href='blog/{post.slug}'>{post.title}</a></li>
	{/each}
</ul>