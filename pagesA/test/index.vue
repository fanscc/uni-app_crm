<template>
	<view class="" @click="go">分包测试</view>
</template>

<script>
	export default {
		methods: {
			go() {
				uni.reLaunch({
				    url: "/pages/index/index"
				})
			}
		}
	}
	
</script>

<style>
</style>
