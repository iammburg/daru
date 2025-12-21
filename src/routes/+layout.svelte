<script lang="ts">
	import './layout.css';

	let { children } = $props();
</script>

<svelte:head>
	<title>Daru</title>
</svelte:head>

{@render children()}
