<script>
	export const prerender = true;
	import Navbar from '../Navbar.svelte';
	import PortraitPhotos from './PortraitPhotos.svelte';
</script>

<body>
	<Navbar />
	<section id="portraits" class="container">
		<p class="title">Families and couples, engagement, maternity, & more.</p>
		<PortraitPhotos />
		<p class="prevSection">
			<a href="/landscape" data-sveltekit-preload-data="tap"
				><span class="next">&lsaquo;</span> Landscape</a
			>
		</p>
	</section>
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
	a {
		text-decoration: none;
		color: black;
	}
	.container {
		max-width: 1280px;
		padding: 0 1.5rem;
		margin: auto;
	}

	.title {
		text-align: center;
		font-size: 16px;
		margin: 3rem 0 7rem 0;
	}
	.prevSection {
		font-weight: 900;
		text-align: left;
		font-size: 25px;
		margin: 5rem 0;
	}
	.next {
		font-size: 30px;
		margin-left: 5px;
	}

	/* Media Query */
	@media (max-width: 500px) {
		.prevSection {
			font-size: 20px;
		}
	}
</style>
