<script>
	export const prerender = true;
	import Navbar from '../Navbar.svelte';
	import StreetPhotos from './StreetPhotos.svelte';
</script>

<body>
	<Navbar />
	<section id="city" class="container">
		<p class="title">Street & cityscapes.</p>
		<StreetPhotos />
		<p class="nextSection">
			<a href="/landscape" data-sveltekit-preload-data="tap"
				>Landscape <span class="next">&rsaquo;</span></a
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
	.next {
		font-size: 30px;
		margin-left: 5px;
	}
	.nextSection {
		font-weight: 900;
		text-align: right;
		font-size: 25px;
		margin: 5rem 0;
	}

	/* Media Query */
	@media (max-width: 500px) {
		.nextSection {
			font-size: 20px;
		}
	}
</style>
