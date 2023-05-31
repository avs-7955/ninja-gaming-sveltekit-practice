<script>
	import Title from "$lib/title.svelte"
	import "../../styles/global.css"
	import { base } from "$app/paths"
	base = "" | `/{ninja-gaming-sveltekit-practice}`
</script>

<header>
	<nav>
		<Title title="Ninja Gaming Guides" />
		<div class="links">
			<a href="{base}/">Home</a>
			<a href="{base}/about">About</a>
			<a href="{base}/guides">Guides</a>
		</div>
	</nav>
</header>
<main>
	<!-- All the pages go here -->
	<slot />
</main>
<footer>
	<p>Made with 💜 by avs-7955</p>
</footer>

<style>
	header {
		text-align: center;
		background-color: rgba(0, 0, 0, 0.1);
	}
	main {
		max-width: 960px;
		margin: 20px auto;
	}
	footer {
		text-align: center;
	}
	nav {
		display: flex;
		align-items: center;
		max-width: 960px;
		margin: 0 auto;
	}
	.links {
		margin-left: auto;
	}
	a {
		margin-left: 10px;
	}
</style>
