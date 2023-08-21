<div class="enter-btn">
	<a href="/home">Enter Site</a>
</div>

<style>
	.enter-btn {
		display: grid;
		height: 100dvh;
		text-align: center;
		align-items: center;
	}
	a {
		margin: 0 auto;
		background-image: linear-gradient(to right, rgba(166, 52, 19, 0), rgba(166, 52, 19, 0.2));
		border: 2px solid red;
		border-radius: 0.1em;
		width: 10dvw;
		text-decoration: none;
		color: #dc400f;
		font-weight: bold;
		letter-spacing: 0.5rem;
		font-size: 2em;
		cursor: pointer;
	}

	a:hover {
		background-color: #dc400f;
		border: 2px solid #dc400f;
		color: antiquewhite;
	}

	@media screen and (max-width: 480px) {
		a {
			width: 40dvw;
		}
	}
	@media screen and (min-width: 481px) {
		a {
			width: 20dvw;
		}
	}
	@media screen and (min-width: 1199px) {
		a {
			width: 10dvw;
		}
	}
</style>
