<script setup lang="ts">
import HeaderItem from '@/components/HeaderItem.vue'
import HeaderLinkItem from '@/components/HeaderLinkItem.vue'
</script>

<template>
	<header class="flex md:px-[20%] bg-gray-800 text-white">
		<HeaderItem class="flex-1">
			<HeaderLinkItem to="/">Eduarda Dal Bianco Guedes</HeaderLinkItem>
		</HeaderItem>
		<HeaderItem>
			<HeaderLinkItem to="/about">Sobre mim</HeaderLinkItem>
		</HeaderItem>
		<HeaderItem>
			<HeaderLinkItem to="/work">Profissional</HeaderLinkItem>
		</HeaderItem>
		<HeaderItem>
			<HeaderLinkItem to="/experiences">Experiência</HeaderLinkItem>
		</HeaderItem>
		<HeaderItem>
			<HeaderLinkItem to="/contact">Contato</HeaderLinkItem>
		</HeaderItem>
	</header>
</template>
