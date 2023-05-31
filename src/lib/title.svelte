<script>
	export let title = "Gaming Ninja"
</script>

<div class="title">
	<img src="/logo.svg" alt="Logo" />
	<h1>{title}</h1>
</div>

<style>
	.title {
		display: flex;
	}
	.title img {
		display: inline-block;
		filter: invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg)
			brightness(100%) contrast(90%);
	}
	.title h1 {
		margin-left: 10px;
		min-width: fit-content;
	}
</style>
