<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
	<RouterLink to="/" class="px-4 py-8 cursor-pointer hover:bg-gray-700">
		<slot></slot>
	</RouterLink>
</template>
