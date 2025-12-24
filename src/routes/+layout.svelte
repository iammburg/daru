<script lang="ts">
	import './layout.css';
	import Navbar from '$lib/components/ui/navbar/navbar.svelte';

	let { children } = $props();
</script>

<svelte:head>
	<title>Daru</title>
	
</svelte:head>

<Navbar />

{@render children()}

<style>
	:global(body) {
		max-width: 1440px;
		margin: auto;
	}
</style>
