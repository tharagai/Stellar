<style>

</style>

<script>
	import {
		onMount
	} from 'svelte';
	onMount(() => {
		console.log('Functions are coming...');

		fetch("/.netlify/functions/hello")
			.then(response => response.json())
			.then(json => console.log(json))
	});
</script>

<svelte:head>
	<title>Sapper netflify jamstack template</title>
</svelte:head>

<section class="js-parallax u-promo-block u-promo-block--mheight-600 u-overlay u-overlay--dark text-white">
	<!-- Promo Content -->
	<div class="container u-overlay__inner u-ver-center u-content-space">
		<div class="row justify-content-center">
			<div class="col-12">
				<div class="text-left">
					<h1 class="display-sm-4 display-lg-3 mb-3">We build delightful digital experiences.
						<span class="js-display-typing"></span><span class="typed-cursor"></span></h1>
					<p class=" u-letter-spacing-sm mb-0">Cheesecake Labs is a software design and engineering partner
						that helps you build successful tech products.</p>
					<a class="btn btn-primary" href="services.html">
						Learn More <i class="fas fa-arrow-alt-circle-right ml-2"></i>
					</a>
				</div>
			</div>
		</div>
	</div>
</section>