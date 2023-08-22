<script>
	let date = new Date().getFullYear();
</script>

<div>
	<h1>Dale Bendixen &copy; {date}</h1>
	<h3>This site built with Svelte-Kit</h3>
</div>

<style>
	div {
		display: grid;
		grid-template-columns: 1fr 1fr;
		justify-items: center;
		align-items: center;
	}

	@media screen and (max-width: 480px) {
		div {
			width: 80dvw;
			margin: 16em auto 2em auto;
		}
		h1 {
			font-size: 1em;
		}
		h3 {
			font-size: 0.8em;
		}
	}
</style>
