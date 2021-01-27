<template>
	<view class="container">
		<view class="d-table border">
			<view class="d-tr">
				<view class="d-th">张三</view>
				<view class="d-th border-left">李四</view>
				<view class="d-th border-left">王五</view>
			</view>
		</view>
		<scroll-view style="height: 200upx;" class="border-bottom" scroll-y>
			<view class="d-table border" style="border-top: 0;border-bottom: 0;">
				<view class="d-tr" v-for="i in 10" :key="i">
					<view class="d-td" :class="{'border-top':i>1}">张三</view>
					<view class="d-td border-left" :class="{'border-top':i>1}">李四</view>
					<view class="d-td border-left" :class="{'border-top':i>1}">王五</view>
				</view>
			</view>
		</scroll-view>
	</view>
</template>

<script>
export default {
	data() {
		return {};
	}
};
</script>

<style lang="scss">
.container {
	padding: 10rpx;
}
</style>
