<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<div class="flex flex-col min-h-screen">
	<header class="border-b-2 border-gray-400 p-4">
		<h1 class=" text-2xl font-semibold">Dance Brawler | Small Bag O' Peas</h1>
	</header>
	
	<main class="flex-1">
		{@render children()}
	</main>
	
	<footer class="border-t-2 border-gray-400 text-center p-4">
		<h1>&copy; Small Bag O' Peas 2025</h1>
	</footer>
</div>