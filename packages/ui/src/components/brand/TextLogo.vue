<template>
	<span class="text-lg font-bold tracking-tight" :class="{ 'animate-pulse': animate }">App</span>
</template>

<script setup>
defineProps({
	animate: {
		type: Boolean,
		default: false,
	},
})
</script>