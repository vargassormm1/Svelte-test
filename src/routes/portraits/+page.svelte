<script>
	export const prerender = true;
	import Nav from './Nav.svelte';
	import HeaderContent from './HeaderContent.svelte';
</script>

<body>
	<header id="home">
		<div class="container">
			<Nav />
			<HeaderContent />
		</div>
	</header>
</body>

<style>
	* {
		margin: 0;
		padding: 0;
	}
	body {
		font-family: 'ITC Avant Garde Gothic Std Book', sans-serif;
		line-height: 1.6;
		background: white;
	}
	#home {
		background: url('https://ik.imagekit.io/swlh9sefiw4t/background_e-YfotTVE.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672377520499')
			no-repeat center right/cover;
		height: 100vh;
		color: white;
	}
	.container {
		max-width: 1280px;
		padding: 0 1.5rem;
		margin: auto;
	}

	/* Media Query */
	@media (max-width: 550px) {
		#home {
			background-image: none;
			height: 30rem;
			color: white;
		}
		#home .container {
			background: url('https://ik.imagekit.io/swlh9sefiw4t/phoneBackground_ry41R0qp7.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672520947963')
				no-repeat center right/cover;
			width: auto;
			height: 100vh;
		}
	}
</style>
