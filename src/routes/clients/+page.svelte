<script>
	export const prerender = true;
	import Navbar from '../Navbar.svelte';
	import ClientContent from './ClientContent.svelte';
</script>

<body>
	<Navbar />
	<ClientContent />
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
</style>
