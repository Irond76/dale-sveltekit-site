<script>
	import PersonalComponent from '../../components/PersonalComponent.svelte';
	import ProfessionalComponent from '../../components/ProfessionalComponent.svelte';
	import { fade } from 'svelte/transition';
</script>

<div class="back">
	<a href="/home">Home</a>
</div>
<main>
	<div in:fade={{ delay: 250, duration: 1000 }}>
		<ProfessionalComponent />
	</div>
	<div in:fade={{ delay: 750, duration: 1000 }}><PersonalComponent /></div>
</main>

<style>
	main {
		/* border: 1px solid blue; */
		display: grid;
		grid-template-columns: 1fr 1fr;
		justify-items: center;
		align-items: center;
		margin: 0 auto;
		width: 80dvw;
		height: 80dvh;
	}
	.back {
		margin: 1em 0 0 1em;
	}
	a {
		text-decoration: none;
		color: red;
	}
	a:hover {
		color: #fff;
	}

	@media screen and (max-width: 480px) {
		main {
			grid-template-columns: 1fr;
			height: 60dvh;
		}
	}
</style>
