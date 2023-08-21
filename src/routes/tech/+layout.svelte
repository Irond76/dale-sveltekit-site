<script>
	import DaleNoTransition from '../../components/DaleNoTransition.svelte';
	import Footer from '../../components/Footer.svelte';
	import { fade } from 'svelte/transition';
</script>

<DaleNoTransition />
<div in:fade={{ delay: 300, duration: 1000 }}>
	<slot />
</div>
<Footer />
