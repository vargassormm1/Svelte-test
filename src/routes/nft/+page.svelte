<script>
	export const prerender = true;
	import Navbar from '../Navbar.svelte';
	import NftContent from './NftContent.svelte';
</script>

<body>
	<Navbar />
	<NftContent />
</body>

<style>
	/* General Styles */
	* {
		margin: 0;
		padding: 0;
	}
	body {
		font-family: 'ITC Avant Garde Gothic Std Book', sans-serif;
		line-height: 1.6;
		background: white;
	}
</style>
