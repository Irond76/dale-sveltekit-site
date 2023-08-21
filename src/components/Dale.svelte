<script>
	import { fly } from 'svelte/transition';
</script>

<div class="container">
	<div transition:fly={{ delay: 100, duration: 1000, x: 2000, y: 10, opacity: 0 }} class="myName">
		<h2>Dale Bendixen</h2>
	</div>
	<div transition:fly={{ delay: 300, duration: 1000, x: 2000, y: 10, opacity: 0 }} class="hashes">
		<h2>//</h2>
	</div>
	<div transition:fly={{ delay: 500, duration: 1000, x: 2000, y: 10, opacity: 0 }} class="Devloper">
		<h2>Developer</h2>
	</div>
</div>
<hr />

<style>
	.container {
		/* border: 1px solid blue; */
		margin-top: 0rem;
		/* background-color: rgba(166, 52, 19, 0.1); */
		padding: 0.5rem;
	}
	.myName {
		margin: 0rem 0 0 1.5rem;
	}
	.hashes {
		margin: -1.3rem 0 0 12rem;
		color: red;
	}

	.Devloper {
		margin: -1.5rem 0 0 14rem;
	}
	hr {
		height: 1px;
		background-color: red;
		border: none;
	}
</style>
