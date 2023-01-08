<script>
	export const prerender = true;
</script>

<div class="client-section">
	<p>Real Estate (various clients)</p>
	<div class="clientImages">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Real_Estate/1_PVv34BGfY.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672466339763"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Real_Estate/2_gsyLhbjkx.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672466339796"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Real_Estate/3_h05DYaRe3.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672466339762"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Real_Estate/4_OvCxPuVh1.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672466339880"
			alt=""
		/>
	</div>
</div>

<style>
	* {
		margin: 0;
		padding: 0;
	}
	.client-section {
		margin-bottom: 3rem;
	}
	.client-section p {
		font-family: 'ITC Avant Garde Gothic Std Bold', sans-serif;
	}
	.clientImages {
		display: flex;
	}
	.clientImages img {
		width: 250px;
		margin-right: 10px;
	}
	/* Media Query */
	@media (max-width: 500px) {
		.client-section {
			margin-bottom: 3rem;
		}
		.client-section p {
			font-family: 'ITC Avant Garde Gothic Std Bold', sans-serif;
			text-align: center;
		}
		.clientImages {
			display: flex;
			flex-direction: column;
			padding: 3rem;
		}
		.clientImages img {
			width: 100%;
			height: auto;
			margin-bottom: 10px;
		}
	}
</style>
