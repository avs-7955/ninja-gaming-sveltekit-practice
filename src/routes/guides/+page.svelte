<script>
	// getting the guides from the +page.js
	export let data
	let guides = data.props.guides
	import { base } from "$app/paths"
	base = "" | `/{ninja-gaming-sveltekit-practice}`
</script>

<div class="guides">
	<ul>
		{#each guides as guide}
			<li>
				<!-- prefetching the data, when the user hovers over the tag -->
				<a
					data-sveltekit-preload-data="hover"
					href="{base}/guides/{guide.id}">{guide.title}</a
				>
			</li>
		{/each}
	</ul>
</div>

<style>
	.guides {
		margin-top: 20px;
	}
	ul {
		list-style-type: none;
		padding: 0;
	}
	a {
		display: inline-block;
		margin-top: 10px;
		padding: 10px;
		border: 1px dotted rgba(255, 255, 255, 0.2);
	}
</style>
