<script>
	import { page } from "$app/stores"
	import { base } from "$app/paths"
	// base = "" | `/{ninja-gaming-sveltekit-practice}`
</script>

<div class="error">
	<h1>{$page.status}: {$page.error.message}</h1>
	<a href="{base}/guides">View all Guides...</a>
</div>

<style>
	.error {
		text-align: center;
		margin-bottom: 60px;
	}
</style>
