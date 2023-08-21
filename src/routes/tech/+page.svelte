<script>
	import { fade } from 'svelte/transition';
</script>

<div class="back">
	<a href="/home">Home</a>
</div>
<div class="wrapper">
	<div class="container" in:fade={{ delay: 300, duration: 1000 }}>
		<div>
			<h1 class="title">Technologies:</h1>
		</div>
		<div>
			<p>PYTHON</p>
			<p>SQL</p>
			<p>HTML</p>
			<p>CSS</p>
			<p>JAVASCRIPT</p>
			<p>BOOTSTRAP</p>
			<p>REACT</p>
			<p>REACT-NATIVE</p>
			<p>NODE AND EXPRESSJS</p>
			<p>MONGODB</p>
			<p>SVELTE</p>
			<p>SVELTE-KIT</p>
		</div>
	</div>
</div>

<style>
	.wrapper {
		background-color: rgba(50, 50, 50, 0.3);
		border-radius: 1em;
		padding: 1em;
		width: 100dvw;
		margin: 2em 0 5em 0;
	}
	.container {
		margin: 4em auto 2em auto;
		border: 1px solid #dc400f;
		border-radius: 1em;
		padding: 1em;
		width: 90dvw;
	}
	.title {
		text-decoration: underline;
		margin-bottom: 0.2em;
	}
	a {
		color: #fff;
		text-decoration: none;
		cursor: pointer;
	}
	a:hover {
		color: #fff;
	}
	.back {
		margin: 1em 0 0 1em;
	}
	a {
		text-decoration: none;
		color: red;
	}
</style>
