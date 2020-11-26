<script>
	export let segment;
</script>

<style>
	nav {
		border-bottom: 1px solid rgba(255,62,0,0.1);
		font-weight: 300;
		padding: 0 1em;
	}

	ul {
		margin: 0;
		padding: 0;
	}

	/* clearfix */
	ul::after {
		content: '';
		display: block;
		clear: both;
	}

	li {
		display: block;
		float: left;
	}

	.selected {
		position: relative;
		display: inline-block;
	}

	.selected::after {
		position: absolute;
		content: '';
		width: calc(100% - 1em);
		height: 2px;
		background-color: rgb(255,62,0);
		display: block;
		bottom: -1px;
	}

	a {
		text-decoration: none;
		padding: 1em 0.5em;
		display: block;
	}
</style>
<header>
	<!-- Navbar -->
	<nav class="js-navbar-scroll navbar fixed-top navbar-expand-lg navbar-dark navbar-bg-onscroll--fade">
	  <div class="container-fluid">
		<a class="navbar-brand" href="home-page.html">
			<svg width="60" height="60" xmlns="http://www.w3.org/2000/svg">
				<!-- Created with Method Draw - http://github.com/duopixel/Method-Draw/ -->
			   
				
				<g>
				 <title>Layer 1</title>
				 <!-- Created with Method Draw - http://github.com/duopixel/Method-Draw/ -->
				 <g stroke="null" id="svg_44">
				  <g stroke="null" id="svg_42">
				   <title stroke="null" transform="translate(0,8.45643424987793) translate(10.999876022338867,0) matrix(0.08159879734803316,0.14133326284331,-0.14133326284331,0.08159879734803316,20.835138982578435,-60.601584217368604) ">background</title>
				  </g>
				  <g stroke="null" transform="matrix(0.08159879734803316,0.14133326284331,-0.14133326284331,0.08159879734803316,158.3414994932203,-995.9763755729965) " id="svg_43">
				   <title stroke="null" transform="translate(44.874969482421875,25.9085750579834) translate(33.70109558105469,-58.372013092041016) translate(-2.330975294113159,-1.3457891941070557) translate(8.759488105773926,-15.17187786102295) translate(-152.74249267578125,-12.823129653930664) translate(72.27903747558594,54.29078674316406) translate(8.154304504394531,4.707889556884766) translate(0.00004570940654957667,-0.00007917101902421564) translate(-38.171539306640625,-47.71442413330078) translate(-0.00026392334257252514,0) translate(-9.094947017729282e-13,0.5947861075401306) translate(19.085769653320312,9.542884826660156) translate(-22.26673126220703,-3.1809616088867188) translate(-0.00008406963024754077,-0.00004853762220591307) translate(-372.1725158691406,-330.82000732421875) translate(-947.9265747070312,-601.2017822265625) translate(6000,0) translate(0,4500) ">Layer 1</title>
				   <g stroke="null" id="svg_22">
					<g stroke="null" id="svg_23">
					 <g stroke="null" id="svg_38" transform="matrix(1,0,0,1,314.602,33.856) " display="inline">
					  <path stroke="null" d="m4736.40804,3617.2468l74.699,129.382l74.699,129.384l-149.398,0l-149.398,0l74.699,-129.384l74.699,-129.382z" fill="#56aaff" stroke-linecap="square" id="svg_39"/>
					 </g>
					 <g stroke="null" id="svg_36" transform="matrix(-1,-1.2246467991473532e-16,1.2246467991473532e-16,-1,613.865,380.4800000000001) " display="inline">
					  <path stroke="null" d="m-4437.61204,-3617.2468l74.699,129.382l74.699,129.384l-149.398,0l-149.398,0l74.699,-129.384l74.699,-129.382z" fill="#56aaff" stroke-linecap="square" id="svg_37"/>
					 </g>
					 <g stroke="null" id="svg_34" transform="matrix(1,0,0,1,314.602,33.856) " display="inline">
					  <path stroke="null" d="m4587.01004,3875.711l0.2256,-0.3908l0.0285,0.3908l-0.2541,0zm99.14,0l-0.0238,0l0.1468,-0.0632l50.3092,-258.401l0.0588,0.1018l0,345.8152l-50.491,-87.4528z" fill="#4ca0ef" stroke-linecap="square" id="svg_35"/>
					 </g>
					 <g stroke="null" id="svg_32" transform="matrix(1,0,0,1,464.00000000000006,34) " display="inline">
					  <path stroke="null" d="m4736.64104,3875.7108l-0.226,-0.391l-0.028,0.391l0.254,0zm-99.14,0l0.024,0l-0.147,-0.063l-50.309,-258.401l-0.059,0.102l0,345.815l50.491,-87.453z" fill="#4392d8" stroke-linecap="square" id="svg_33"/>
					 </g>
					 <g stroke="null" id="svg_30" transform="matrix(1,0,0,1,515,121.689) " display="inline">
					  <path stroke="null" fill="#378fe8" stroke-linecap="square" d="m4587.01004,3617.2468l49.333,85.1l3,-5.147l-52.333,-79.953z" id="svg_31"/>
					 </g>
					 <g stroke="null" id="svg_28" transform="matrix(1,0,0,1,361,121.714) " display="inline">
					  <path stroke="null" d="m4639.34304,3617.2468l-49.333,85.1l-3,-5.147l52.333,-79.953z" fill="#378fe8" stroke-linecap="square" id="svg_29"/>
					 </g>
					 <g stroke="null" id="svg_26" transform="matrix(1,0,0,1,314.602,33.856) " display="inline">
					  <path stroke="null" fill="#75baff" stroke-linecap="square" d="m4736.40804,3617.2468l-149.398,258.766l46.398,0l103,-258.766z" id="svg_27"/>
					 </g>
					 <g stroke="null" id="svg_24" transform="matrix(1,0,0,1,464,33.856) " display="inline">
					  <path stroke="null" d="m4587.01004,3617.2468l149.398,258.766l-46.398,0l-103,-258.766z" fill="#75baff" stroke-linecap="square" id="svg_25"/>
					 </g>
					</g>
				   </g>
				  </g>
				 </g>
				</g>
			   </svg>
			   Steller Systems
		</a>

		<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo" aria-controls="navbarTogglerDemo" aria-expanded="false" aria-label="Toggle navigation">
		  <span class="navbar-toggler-icon"></span>
		</button>

		<div class="collapse navbar-collapse" id="navbarTogglerDemo">
		  

		  <ul class="navbar-nav ml-auto mt-2 mt-lg-0">
			<li class="nav-item mr-4 mb-2 mb-lg-0">
				<a class='{segment === undefined ? "active" : ""}' href='.'>home</a>
			</li>
			<li class="nav-item mr-4 mb-2 mb-lg-0">
				<a class='{segment === "about" ? "active" : ""}' href='about'>about</a>
			</li>
		
			<li class="nav-item mr-4 mb-2 mb-lg-0">
				<a rel=prefetch class='{segment === "blog" ? "selected" : ""}' href='blog'>blog</a>
			</li>
		  </ul>
		  <div>
			<a class="btn btn-primary p-1" data-toggle="modal" href="#callUsModal">
			  <i class="fas fa-phone-square mr-1"></i> Contact us
			</a>
		  </div>
		</div>
	  </div>
	</nav>
	<!-- End Navbar -->


	<!-- End Promo Block -->
  </header>
