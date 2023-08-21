<script>
	import Footer from '../../components/Footer.svelte';
	import { fade } from 'svelte/transition';
	import DaleNoTransition from '../../components/DaleNoTransition.svelte';
</script>

<DaleNoTransition />
<div in:fade={{ delay: 250, duration: 1000 }}>
	<slot />
</div>
<Footer />
