<template>
	<div
		class="flex items-center gap-2 cursor-pointer w-full px-2 py-1 rounded-lg hover:bg-stone-200 transition-background duration-150"
		:class="{ 'bg-stone-200': active }"
	>
		<Icon
			:name="iconName"
			mode="svg"
			size="1.2em"
			class="pointer-events-none"
			:class="active ? 'text-black' : 'text-neutral-500'"
		/>
		<label
			class="pointer-events-none"
			:class="active ? 'text-black' : 'text-neutral-500'"
		>
			{{ iconText }}
		</label>
	</div>
</template>

<script setup lang="ts">
defineProps({
	iconName: {
		type: String,
		default: 'tabler:home',
	},
	iconText: {
		type: String,
		default: 'Home',
	},
	active: {
		type: Boolean,
		default: false,
	},
});
</script>