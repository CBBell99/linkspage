<script>
import IoLogoGithub from 'svelte-icons/io/IoLogoGithub.svelte'
import IoLogoInstagram from 'svelte-icons/io/IoLogoInstagram.svelte'
import IoLogoLinkedIn from 'svelte-icons/io/IoLogoInstagram.svelte'
import IoLogoChrome from 'svelte-icons/io/IoLogoInstagram.svelte'
</script>

<main class="main">
	<header>
		<h1>Linktree, but free</h1>
	</header>
	<div class="btn">
    
		<a href="https://chrisbellwebdev.vercel.app">My Portfolio Website</a>
	</div>
	<div class="btn">
		<a href="https://github.com/CBBell99">My Github Page</a>
	</div>
	<div class="btn">
		<a href="https://www.instagram.com/humperpump">Instagram</a>
	</div>
	<div class="btn">
		<a href="www.linkedin.com/chrisbeckertonbell">LinkedIn</a>
	</div>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap');

	.main {
		width: 100%;
		background: linear-gradient(#4ca9c1, #091e8d);
		height: 100vh;
		display: flex;
		flex-direction: column;
		align-items: center;
	}
	h1 {
		font-family: 'Inter', sans-serif;
		color: white;
	}
	.btn {
		display: flex;
    justify-content: flex-start;
		align-items: center;
		border: 1px white solid;
		border-radius: 30px;
		height: 3.5rem;
		max-width: 40rem;
		width: 100%;
		margin: 10px;
	}

	a {
		text-decoration: none;
		font-family: Inter;
		color: white;
	}
</style>
