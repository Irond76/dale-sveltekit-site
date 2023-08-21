<script>
	import Dale from '../../components/Dale.svelte';
	import SkillsComponent from '../../components/SkillsComponent.svelte';
	import EducationComponent from '../../components/EducationComponent.svelte';
	import { fade } from 'svelte/transition';
	import AboutMeComponent from '../../components/AboutMeComponent.svelte';
</script>

<main>
	<div in:fade={{ delay: 1500, duration: 1000 }}><AboutMeComponent /></div>
	<div in:fade={{ delay: 2500, duration: 1000 }}><SkillsComponent /></div>
	<div in:fade={{ delay: 3500, duration: 1000 }}><EducationComponent /></div>
</main>

<style>
	main {
		/* border: 1px solid blue; */
		display: grid;
		grid-template-columns: 1fr 1fr 1fr;
		justify-items: center;
		align-items: center;
		margin: 0 auto;
		width: 80dvw;
		height: 80dvh;
	}

	@media screen and (max-width: 480px) {
		main {
			grid-template-columns: 1fr;
			height: 60dvh;
		}
	}
</style>
