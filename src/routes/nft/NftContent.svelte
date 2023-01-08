<script>
	export const prerender = true;
	import HelloEuphoria from './HelloEuphoria.svelte';
	import Usd from './Usd.svelte';
	import OneOfOne from './OneOfOne.svelte';
</script>

<section class="nftContainer">
	<p class="title">All my NFT work and links to projects below</p>
	<HelloEuphoria />
	<Usd />
	<OneOfOne />
</section>

<style>
	/* General Styles */
	* {
		margin: 0;
		padding: 0;
	}
	.nftContainer {
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

	/* Media Query */
	@media (max-width: 500px) {
		.nftContainer {
			display: flex;
			flex-direction: column;
			justify-content: center;
			align-items: center;
		}
	}
</style>
