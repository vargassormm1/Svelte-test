<script>
	export const prerender = true;
	import AtlanticRetail from './AtlanticRetail.svelte';
	import VentureHeat from './VentureHeat.svelte';
	import RealEstate from './RealEstate.svelte';
</script>

<!-- Photos -->
<section class="clientContainer">
	<p class="title">A mix of commercial work for various companies and brands I've worked with.</p>
	<AtlanticRetail />
	<VentureHeat />
	<RealEstate />
</section>

<style>
	* {
		margin: 0;
		padding: 0;
	}
	.clientContainer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	.title {
		text-align: center;
		font-size: 16px;
		margin: 3rem 0 7rem 0;
	}

	@media (max-width: 500px) {
		.clientContainer {
			display: flex;
			flex-direction: column;
			justify-content: center;
			align-items: center;
		}
	}
</style>
