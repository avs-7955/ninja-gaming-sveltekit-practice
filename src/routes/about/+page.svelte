<script>
	import { base } from "$app/paths"
	// base = "" | `/{ninja-gaming-sveltekit-practice}`
</script>

<div class="about">
	<h2>About Us</h2>
	<p>
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel eaque
		asperiores, fugit ratione eveniet eos magni, cum harum enim iusto iure
		ipsam maxime ab magnam laborum id omnis culpa possimus.
	</p>
	<a href="{base}/guides">View Guides</a>
	<a href="{base}/">Home</a>
</div>

<style>
	.about {
		text-align: center;
		display: block;
		margin: 20px auto;
	}
	a {
		margin: 10px;
	}
</style>
