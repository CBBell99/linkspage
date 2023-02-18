<script>
	import IoLogoGithub from 'svelte-icons/io/IoLogoGithub.svelte';
	import IoLogoInstagram from 'svelte-icons/io/IoLogoInstagram.svelte';
	import IoLogoLinkedIn from 'svelte-icons/io/IoLogoLinkedIn.svelte';
	import IoLogoChrome from 'svelte-icons/io/IoLogoChrome.svelte';
</script>

<main class="main">
	<header>
		<h1>Linktree, but free</h1>
	</header>

	<a href=""><div></div> </a>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap');

	.main {
		/* flex:1; */
		background: linear-gradient(#4ca9c1, #091e8d);
		height: 100vh;
		max-width: 100%;
		padding: 4rem 1rem 2rem 1rem;
		color: white;
		/* margin */
	}

	header {
		display: flex;
		justify-content: center;
	}

	header > h1 {
		font-family: 'Inter', sans-serif;
	}

	.container {
		width: 100%;
		margin: auto;
	}
	.btn {
		width: 100%;
		height: 3.5rem;
		border: 1px white solid;
		display: flex;
		padding: 0 8px;
	}

	.icon {
		color: white;
		height: 2rem;
		width: 2rem;
	}
</style>
