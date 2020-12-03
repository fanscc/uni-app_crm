<template>
	<view>
	<view class="">分包内容</view>
	<view class="" @click="gotoapi">
		分包跳转
	</view>
	</view>
</template>

<script>
	export default {
		methods: {
			gotoapi() {
				console.log(1, 222)
				uni.navigateTo({
				    url: "/pagesA/test/index"
				})
			}
		}
	}
</script>

<style>
</style>
