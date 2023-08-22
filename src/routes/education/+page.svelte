<script>
	import { fade } from 'svelte/transition';
</script>

<div class="back">
	<a href="/home">Home</a>
</div>
<div class="wrapper">
	<div>
		<h1 class="title">Certificates:</h1>
	</div>
	<div class="container" in:fade={{ delay: 300, duration: 1000 }}>
		<div class="image">
			<img src="be-ch.jpg" alt="certificate" width="300px" />
		</div>
		<div class="image">
			<img src="front-end-certificate-honor.jpg" alt="certificate" width="300px" />
		</div>
		<div class="image">
			<img src="python.jpg" alt="certificate" width="300px" />
		</div>
		<div class="image">
			<img src="sql.jpg" alt="certificate" width="300px" />
		</div>
		<div class="image">
			<img src="boot.jpg" alt="certificate" width="300px" />
		</div>
		<div class="image">
			<img src="react.jpg" alt="certificate" width="300px" />
		</div>
		<div class="image">
			<img src="react-native.jpg" alt="certificate" width="300px" />
		</div>
		<div class="image">
			<img src="web-fund.jpg" alt="certificate" width="300px" />
		</div>
	</div>
</div>

<style>
	.wrapper {
		background-color: rgba(50, 50, 50, 0.3);
		border-radius: 1em;
		padding: 1em;
		width: 100dvw;
	}
	.container {
		margin: 4em auto 2em auto;
		border: 1px solid #dc400f;
		border-radius: 1em;
		padding: 1em;
		width: 90dvw;
		display: grid;
		grid-template-columns: 1fr 1fr 1fr 1fr;
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
	.image {
		text-align: center;
		margin-bottom: 2em;
	}
	.title {
		margin-bottom: 2em;
	}

	@media screen and (max-width: 480px) {
		.container {
			grid-template-columns: 1fr;
		}
	}
	@media screen and (min-width: 481px) {
		.container {
			grid-template-columns: 1fr 1fr;
		}
	}
	@media screen and (min-width: 1300px) {
		.container {
			grid-template-columns: 1fr 1fr 1fr 1fr;
		}
	}
</style>
