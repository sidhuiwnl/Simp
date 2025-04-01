<script>
	const prompts = [
		"Summarize this article",
		"Generate a study guide",
		"Explain this code",
		"Suggest project ideas",
		"Improve my resume",
		"Summarize this article"
	];
	import { Button } from '$lib/components/ui/button/index.js';
</script>

<div class="flex flex-col items-center py-32">
	<h1 class="text-4xl font-medium mb-6">How can I help you?</h1>

	<div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4 mt-10">
		{#each prompts as prompt}
			<Button variant="ghost" class="px-4 py-2  transition">
				<span class="text-lg">{prompt}</span>
			</Button>
		{/each}
	</div>
</div>
