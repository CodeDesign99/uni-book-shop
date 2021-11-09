<template>
	<view class="content">
		首页
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		async onLoad() {
			// this.$u.post('api/auth/login').then(res => {
			// 	console.log(res)
			// })
			const res = await this.$u.patch('api/orders/1/confirm', {name: 'Tom'})
			console.log(res)
		},
		methods: {

		}
	}
</script>

<style lang="scss" scoped>
	
</style>
