<script>
	import { fly, fade } from 'svelte/transition';
</script>

<div class="wrapper">
	<div class="container">
		<div transition:fly={{ delay: 100, duration: 1000, x: 2000, y: 10, opacity: 0 }} class="myName">
			<h2>Dale Bendixen</h2>
		</div>
		<div transition:fly={{ delay: 300, duration: 1000, x: 2000, y: 10, opacity: 0 }} class="hashes">
			<h2>//</h2>
		</div>
		<div
			transition:fly={{ delay: 500, duration: 1000, x: 2000, y: 10, opacity: 0 }}
			class="Devloper"
		>
			<h2>Developer</h2>
		</div>
	</div>
	<div class="phone" in:fade={{ delay: 1200, duration: 1000 }}>
		<a href="tel:2084129197">
			<h3>Phone: 208-412-9197</h3>
		</a>
	</div>
	<div class="email" in:fade={{ delay: 2000, duration: 1000 }}>
		<a href="mailto:dalebendixen@gmail.com" target="_blank" rel="noopener noreferrer"
			><h3>Contact Me</h3></a
		>
	</div>
</div>
<hr />

<style>
	.wrapper {
		/* border: 1px solid blue; */
		display: grid;
		margin: 0 auto;
		width: 80dvw;
		grid-template-columns: 2fr 1fr 1fr;
		align-items: center;
		justify-content: space-between;
	}
	.container {
		/* border: 1px solid blue; */
		margin-top: 0rem;
		padding: 1rem;
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
	a {
		text-decoration: none;
		color: #dc400f;
		cursor: pointer;
	}
	a:hover {
		color: #fff;
	}

	@media screen and (max-width: 1079px) {
		.wrapper {
			display: grid;
			grid-template-columns: 1fr;
			justify-content: center;
			margin-top: 1rem;
		}
		.phone {
			text-align: center;
			margin-bottom: 1rem;
		}
		.email {
			text-align: center;
			margin-bottom: 1rem;
		}
		.Devloper {
			margin-bottom: 1rem;
		}
	}
</style>
