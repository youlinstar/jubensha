<template>
	<view class="uni-container">
		<view v-if="!hasLeftWin" class="uni-header-logo">
			<image class="uni-header-image" src="/static/componentIndex.png"></image>
		</view>
	
	</view>
</template>

<script>
	export default {
		data() {
			return {
				href: 'https://uniapp.dcloud.io/component/README?id=uniui'
			}
		},
		methods: {

		}
	}
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
