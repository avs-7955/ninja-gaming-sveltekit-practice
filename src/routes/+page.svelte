<script>
	import { base } from "$app/paths"
	// base = "" | `/{ninja-gaming-sveltekit-practice}`
</script>

<div class="index">
	<h1>Welcome</h1>
	<p>
		Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolorem
		accusantium facilis itaque molestias harum inventore unde voluptate
		reiciendis ipsum voluptatum? Provident, sequi? Officiis, voluptas sit
		hic explicabo ab distinctio optio.
	</p>
	<a href="{base}/guides">View Guides</a>
	<a href="{base}/about">About Us</a>
</div>

<style>
	.index {
		text-align: center;
		display: block;
		margin: 20px auto;
	}
	a {
		margin: 10px;
	}
</style>
