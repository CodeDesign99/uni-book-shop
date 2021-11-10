<template>
	<view class="content">
		首页{{vuex_user.name}}
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
			// const res = await this.$u.patch('api/orders/1/confirm', {name: 'Tom'})
			// console.log(res)
			
			// 集中管理api
			// const res = await this.$u.api.index()
			// console.log(res)
			// const data = {
			// 	email: 'test@a.com',
			// 	password: '123123'
			// }
			// const res = await this.$u.api.authLogin(data)
			// console.log(res)
			
			// 测试 vuex
			console.log(this.vuex_version)
			// this.$u.vuex('vuex_name', 'Tom')
			console.log(this.vuex_name)
		},
		methods: {

		}
	}
</script>

<style lang="scss" scoped>
	
</style>
