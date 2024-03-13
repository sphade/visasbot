<script lang="ts">
	import Footer from '$lib/components/Footer.svelte';
	import Header from '$lib/components/Header.svelte';
	import '../app.pcss';
</script>

<Header />
<slot />
<Footer />
