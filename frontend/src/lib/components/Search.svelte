<script>
	import { ArrowUp } from '@lucide/svelte';
	import { Button } from '$lib/components/ui/button/index.js';
</script>

<div class="fixed bottom-0 left-1/2 transform -translate-x-1/2 w-full max-w-4xl px-6  ">
	<div class="w-full p-1 pb-0 border rounded-t-2xl bg-neutral-800">
	<div class="bg-neutral-900/90 backdrop-blur-lg rounded-t-xl py-6 px-3 shadow-[0_8px_30px_rgba(0,0,0,0.15)] border border-gray-800/50 flex items-center">
		<input
			type="text"
			placeholder="Type your message here..."
			class="bg-transparent w-full text-gray-300 text-lg focus:outline-none placeholder-gray-500 px-4"
		/>
		<Button
			variant="ghost"
			class="w-10 h-10 rounded-full bg-gradient-to-br from-[#3b5de7] to-[#2541b8] hover:from-[#4468f0] hover:to-[#2c4ad0] flex items-center justify-center shadow-md shadow-blue-900/20 transition-all duration-200"
		>
			<ArrowUp class="w-5 h-5 text-white" />
		</Button>
	</div>
	</div>
</div>