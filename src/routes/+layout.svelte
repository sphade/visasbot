<script lang="ts">
	import '../app.pcss';
	import Header from '$lib/Header.svelte';
</script>

<main class="bg-black text-white">
	<Header />
	<slot />
</main>
