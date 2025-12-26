<script lang="ts">
	import Button from '$lib/components/ui/button/button.svelte';
</script>

<header
	class="sticky top-0 z-999 inline-flex w-full items-center justify-between border-b bg-background px-10 py-4 lg:px-20"
>
	<nav>
		<ul class="inline-flex gap-4 font-bold">
			<li><a href="/">Home</a></li>
			<li><a href="/blog">Blog</a></li>
		</ul>
	</nav>
	<!-- <Button variant="default">Log in</Button> -->
</header>
