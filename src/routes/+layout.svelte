<script>
	import Title from "../lib/title.svelte"
	import "../styles/global.css"
	// export const prerender = true
</script>

<header>
	<Title title="Ninja Gaming Guides" />
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
		display: flex;
		justify-content: center;
	}
	main {
		max-width: 960px;
		margin: 20px auto;
	}
	footer {
		text-align: center;
	}
</style>
