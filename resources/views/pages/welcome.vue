<script setup lang="ts">
import abstract from '@/images/abstract.jpg?webp'
</script>

<template>
	<section class="min-h-screen grid place-items-center">
		<div class="p-3.5 w-full max-w-sm bg-white shadow-xl rounded-2xl">
			<img
				class="w-full h-full object-cover rounded-2xl"
				:src="abstract"
			/>
			<div class="p-2">
				<div class="text-2xl font-bold">
					Here is a title
				</div>
				<div class="pt-2 text-slate-700">
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus quis deleniti dolor, sapiente sit repellendus consequuntur aliquam aperiam fugiat commodi. Debitis odio quo iusto similique quisquam amet quis excepturi esse.
				</div>
			</div>
		</div>
	</section>
</template>