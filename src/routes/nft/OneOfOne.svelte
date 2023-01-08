<script>
	export const prerender = true;
</script>

<div class="nft-section">
	<p>
		<a target="_blank" href="https://foundation.app/@matsefcik?tab=collections" rel="noreferrer"
			>1:1s</a
		>
	</p>
	<div class="nftImages">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/1_1/SLPWK_4Tbwx9BuC.png?ik-sdk-version=javascript-1.4.3&updatedAt=1672523556362"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/1_1/DSC06089_ysKMFW0u-.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672523556052"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/1_1/FINAL_GENESIS_FND_VoxxrZ5j7.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672523556356"
			alt=""
		/>
	</div>
</div>

<style>
	/* General Styles */
	* {
		margin: 0;
		padding: 0;
	}
	a {
		text-decoration: none;
		color: black;
	}
	.nft-section {
		width: 950px;
		margin-bottom: 3rem;
	}
	.nft-section p a {
		font-family: 'ITC Avant Garde Gothic Std Bold', sans-serif;
		border-bottom: 0.5px solid black;
		/* font-size: 12px; */
	}
	.nftImages {
		display: flex;
	}
	.nftImages img {
		width: 120px;
		margin-right: 10px;
	}

	/* Media Query */
	@media (max-width: 500px) {
		.nft-section {
			display: flex;
			flex-direction: column;
			justify-content: center;
			align-items: center;
		}
		.nftImages {
			display: flex;
			flex-direction: column;
		}
		.nftImages img {
			width: 250px;
			margin-bottom: 10px;
		}
	}
</style>
