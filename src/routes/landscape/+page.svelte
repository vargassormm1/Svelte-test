<script>
	export const prerender = true;
	import Navbar from '../Navbar.svelte';
	import LandscapePhotos from './LandscapePhotos.svelte';
</script>

<body>
	<Navbar />
	<section id="landscape" class="container">
		<p class="title">Travel & landscapes.</p>
		<LandscapePhotos />
		<div class="navigation">
			<p class="prevSection">
				<a href="/city" data-sveltekit-preload-data="tap"
					><span class="next">&lsaquo;</span> Street</a
				>
			</p>
			<p class="nextSection">
				<a href="/portraits" data-sveltekit-preload-data="tap"
					>Portraits <span class="next">&rsaquo;</span></a
				>
			</p>
		</div>
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
	.navigation {
		display: flex;
		justify-content: space-between;
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
		.prevSection {
			font-size: 20px;
		}
	}
</style>
