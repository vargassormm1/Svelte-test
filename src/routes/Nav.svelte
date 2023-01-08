<script>
	export const prerender = true;
</script>

<nav id="home-nav">
	<a href="/"><h1 class="logo">Matej Sefcik</h1></a>
	<ul>
		<li><a href="/" data-sveltekit-preload-data="tap">Work</a></li>
		<li><a href="/clients" data-sveltekit-preload-data="tap">Clients</a></li>
		<li><a href="/nft" data-sveltekit-preload-data="tap">NFTs</a></li>
		<li><a href="/aboutme" data-sveltekit-preload-data="tap">About</a></li>
		<li>
			<a href="https://www.instagram.com/matsefcik/" target="_blank" rel="noreferrer"
				><i class="fab fa-instagram" /></a
			>
		</li>
		<li>
			<a href="https://twitter.com/matsefcik" target="_blank" rel="noreferrer"
				><i class="fab fa-twitter" /></a
			>
		</li>
		<li>
			<a
				href="https://www.youtube.com/channel/UCXAUVZzv0HRD_ZkvSxEnAdQ"
				target="_blank"
				rel="noreferrer"><i class="fab fa-youtube" /></a
			>
		</li>
		<li>
			<a href="https://www.linkedin.com/in/matejsefcik/" target="_blank" rel="noreferrer"
				><i class="fab fa-linkedin" /></a
			>
		</li>
	</ul>
</nav>

<style>
	* {
		margin: 0;
		padding: 0;
	}
	a {
		text-decoration: none;
		color: black;
	}
	ul {
		list-style: none;
	}
	#index #home-nav a {
		color: white;
	}
	#home-nav {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 1rem 0.5rem;
		color: white;
	}
	#home-nav .logo {
		font-size: 28px;
		pointer-events: none;
		font-weight: 400;
	}
	#home-nav ul {
		display: flex;
	}
	#home-nav li {
		padding: 1rem 1rem;
		font-weight: 150;
		font-size: 14px;
	}
	#home-nav li a .fab {
		font-size: 16px;
	}
	#home-nav a {
		border-bottom: 0.5px transparent solid;
		transition: border-color 0.5s;
		color: white;
	}
	#home-nav ul li a:hover {
		border-color: white;
	}
	/* Media Query */
	@media (max-width: 550px) {
		#home-nav {
			flex-direction: column;
			justify-content: center;
			padding: 1rem 0;
		}
		#home-nav li {
			padding: 1rem 0.7rem;
		}
	}
</style>
