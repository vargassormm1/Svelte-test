<script>
	export const prerender = true;
</script>

<div class="nft-section">
	<p>
		<a target="_blank" href="https://foundation.app/collection/hello-euphoria" rel="noreferrer"
			>Hello, Euphoria <span class="web">(Foundation)</span></a
		>
	</p>
	<div class="nftImages">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Hello_Euphoria/DSC08114-Pano-Edit_copy_CoiHhJqmD.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672522343717"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Hello_Euphoria/DSC06646_copy_Kn_3JGVac.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672522337100"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Hello_Euphoria/DSC05883-Edit_copy_RU4eOelcw.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672522336610"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Hello_Euphoria/DSC07175_copy_flGbH-Osd.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672522336576"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Hello_Euphoria/DSC07521_copy_OcP4tLCVa.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672522336582"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Hello_Euphoria/DSC07954_copy_kf4lyv6CX.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672522336583"
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
		margin-bottom: 3rem;
	}
	.nft-section p a {
		font-family: 'ITC Avant Garde Gothic Std Bold', sans-serif;
		border-bottom: 0.5px solid black;
		/* font-size: 12px; */
	}
	.nft-section .web {
		font-style: italic;
		font-family: 'ITC Avant Garde Gothic Std Extra Light', sans-serif;
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
			margin: 0 0 10px 0;
		}
	}
</style>
