<script>
	export const prerender = true;
</script>

<div class="client-section">
	<p>Atlantic Retail</p>
	<div class="clientImages">
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Atlantic_Retail/1_smGWk32lr.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672466125288"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Atlantic_Retail/2__M8IINw-O.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672466125377"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Atlantic_Retail/3__E473kPVd.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672466125348"
			alt=""
		/>
		<img
			src="https://ik.imagekit.io/swlh9sefiw4t/City/Atlantic_Retail/4_5yakKdXjZ.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672466148501"
			alt=""
		/>
	</div>
	<div class="qoutes">
		<p class="testimonials">
			"Matej was a pleasure to work with. We were in need of high quality images to update various
			marketing materials and he had a creative and professional approach to our project. Matej was
			very responsive and we received our images just a few days after the photo-shoot."
		</p>
		<p class="testimonials-name">- Grace Little, Social Media and Marketing Specialist</p>
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
	.qoutes {
		width: 100%;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		margin-top: 1rem;
	}
	.client-section .testimonials {
		font-family: 'ITC Avant Garde Gothic Std Extra Light', sans-serif;
		font-style: italic;
		width: 800px;
		text-align: center;
	}
	.client-section .testimonials-name {
		font-family: 'ITC Avant Garde Gothic Std Book Condensed', sans-serif;
		font-style: italic;
		width: 550px;
		font-weight: 500;
		text-align: center;
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
		.qoutes {
			margin-top: 0;
		}
		.client-section .testimonials {
			font-family: 'ITC Avant Garde Gothic Std Extra Light', sans-serif;
			font-style: italic;
			width: 300px;
			text-align: center;
		}
		.client-section .testimonials-name {
			font-family: 'ITC Avant Garde Gothic Std Book Condensed', sans-serif;
			font-style: italic;
			width: 300px;
			font-weight: 500;
			text-align: center;
		}
	}
</style>
