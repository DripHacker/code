<template>
	<span class="text-lg font-bold tracking-tight" :class="{ 'animate-pulse': loading }">App</span>
</template>

<script setup>
defineProps({
	loading: {
		type: Boolean,
		default: false,
	},
	api: {
		type: String,
		default: 'prod',
	},
})
</script>