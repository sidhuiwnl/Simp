<script>
	import { Button } from '$lib/components/ui/button/index.js';
	import ModeToggle from '$lib/components/ui/ModeToggle.svelte';
</script>


<header>
	<div class="flex p-4 flex-row items-center justify-between">
		<h1>Simp</h1>
		<div class="flex items-center mt-3 gap-2">
			<Button class="dark:bg-neutral-800 text-white rounded-lg">Add</Button>
			<ModeToggle/>
		</div>
	</div>
</header>