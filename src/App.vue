<template>
	<v-app>
		<div v-for="(item, index) in items" :key="index" class="mb-3 ml-1">
			<v-btn class="justify-center text-subtitle-2 text-red"
				>{{ item.name }}
			</v-btn>
		</div>
	</v-app>
</template>

<script>
	export default {
		data: () => ({
			items: [{ name: 'item1' }, { name: 'item2' }, { name: 'item3' }]
		})
	}
</script>
