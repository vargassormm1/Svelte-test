<div class="header-content">
	<h1><a href="/city" data-sveltekit-preload-data="tap">Street</a></h1>
	<h1><a href="/landscape" data-sveltekit-preload-data="tap">Landscape</a></h1>
	<h1><a href="/portraits" data-sveltekit-preload-data="tap">Portraits</a></h1>
</div>

<style>
	* {
		margin: 0;
		padding: 0;
	}
	a {
		text-decoration: none;
		color: black;
	}

	.header-content {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 70vh;
	}
	.header-content h1 {
		font-size: 70px;
		margin: 0 2rem;
	}
	.header-content h1 a {
		color: white;
	}
	.header-content h1 a:hover {
		color: lightgray;
	}

	/* Media Query */
	@media (max-width: 550px) {
		.header-content {
			display: flex;
			flex-direction: column;
			justify-content: start;
			align-items: center;
		}
		.header-content h1 {
			font-size: 40px;
			margin: 2rem 0;
		}
		.header-content h1 a {
			color: white;
		}
	}
</style>
