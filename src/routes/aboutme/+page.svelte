<script>
	export const prerender = true;
	import Navbar from '../Navbar.svelte';
	import AboutMe from './AboutMe.svelte';
</script>

<body>
	<Navbar />
	<AboutMe />
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
