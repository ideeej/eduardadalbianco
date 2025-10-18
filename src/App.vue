<script setup lang="ts">
import HeaderComponent from '@/components/HeaderComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue'
import AppContent from '@/components/AppContent.vue'
</script>

<template>
	<div class="flex flex-col min-h-screen">
		<HeaderComponent />
		<main class="flex-1">
			<AppContent>
				<router-view />
			</AppContent>
		</main>
		<FooterComponent />
	</div>
</template>

<style>
@import 'tailwindcss';

/* Global styles */
* {
	font-family: 'Cabin', sans-serif;
	font-optical-sizing: auto;
	font-weight: 400;
	font-style: normal;
	font-variation-settings: 'width' 100;
}
</style>
