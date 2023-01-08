<script>
	export const prerender = true;
</script>

<!-- About Me -->
<section id="aboutme" class="container">
	<!-- About Content -->
	<h1><b>Welcome!</b></h1>
	<div class="aboutContent">
		<div class="bio">
			<p>
				Hi there! I'm Matej and I'm a Slovakian-born photographer based in New Jersey. I picked up a
				camera 4 years ago in college and graduated with a degree in Film Production, and then
				slowly found a love for photography. I can create work in a range of different styles and
				genres, and I love to take on new projects that push my creativity. From photographing
				strangers on the streets of New York City, to chasing light from the mountains to the ocean,
				I strive to create emotion-evoking and eye-catching work. My commercial work ranges from
				product photography, to automotive work, to real estate media.
			</p>
			<p>
				Aside from my life behind the lens, I'm a huge hockey and tennis fan, and I love traveling
				to places that seem otherworldly.
			</p>
			<p>
				Thank you for visiting my site! Feel free to visit my socials to see more of my work and
				personality. I look forward to working with you!
			</p>
			<p class="contactme"><b>Contact me:</b></p>
			<p>sefcikmatej@yahoo.com</p>

			<div class="links">
				<p>
					<a href="https://www.instagram.com/matsefcik/" target="_blank" rel="noreferrer"
						><i class="fab fa-instagram" /></a
					>
				</p>
				<p>
					<a href="https://twitter.com/matsefcik" target="_blank" rel="noreferrer"
						><i class="fab fa-twitter" /></a
					>
				</p>
				<p>
					<a
						href="https://www.youtube.com/channel/UCXAUVZzv0HRD_ZkvSxEnAdQ"
						target="_blank"
						rel="noreferrer"><i class="fab fa-youtube" /></a
					>
				</p>
				<p>
					<a href="https://www.linkedin.com/in/matejsefcik/" target="_blank" rel="noreferrer"
						><i class="fab fa-linkedin" /></a
					>
				</p>
			</div>
		</div>

		<!-- Headshot -->
		<div class="pic">
			<img
				src="https://ik.imagekit.io/swlh9sefiw4t/matejPic_Y2CprlXUV.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1672377704353"
				alt=""
			/>
		</div>
	</div>
</section>

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
	.container {
		max-width: 1280px;
		padding: 0 1.5rem;
		margin: auto;
	}
	/* About Me */
	#aboutme {
		display: flex;
		flex-direction: column;
		justify-content: center;
		margin-top: 2%;
	}
	#aboutme h1 {
		font-family: 'ITC Avant Garde Gothic Std Bold Condensed', sans-serif;
		margin-bottom: 3rem;
		text-align: center;
		font-size: 50px;
	}
	.aboutContent {
		display: flex;
		justify-content: flex-start;
		padding: 0 15rem;
	}
	.bio p {
		font-family: 'ITC Avant Garde Gothic Std Book', sans-serif;
		text-align: left;
		font-size: 14px;
		line-height: 1.7em;
		margin-bottom: 13px;
		font-weight: 100;
	}
	.contactme {
		font-family: 'ITC Avant Garde Gothic Std Bold Condensed', sans-serif;
		margin: 1rem 0;
	}
	.contactme b {
		font-family: 'ITC Avant Garde Gothic Std Bold', sans-serif;
	}
	.links {
		display: flex;
		margin-top: 3rem;
	}
	.links p {
		font-size: 10px;
		margin-right: 1rem;
	}
	.links a i {
		padding: 5px;
		border: 1.5px solid black;
	}
	.pic img {
		align-self: flex-start;
		height: 250px;
		width: auto;
		border-radius: 20px;
		margin: 0 2rem;
		overflow: hidden;
		object-fit: cover;
		object-position: center;
	}
	/* Media Query */
	@media (max-width: 500px) {
		.aboutContent {
			flex-direction: column;
			padding: 0;
		}
		.pic {
			display: flex;
			justify-content: center;
		}
		.pic img {
			align-self: center;
		}
	}
</style>
