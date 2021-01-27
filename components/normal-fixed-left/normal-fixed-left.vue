<template>
	<view class="container" style="display: flex;">
		<view class="d-table border" style="width: 30%;">
			<view class="d-tr" v-for="i in 4" :key="i"><view class="d-td border-top">张三</view></view>
		</view>
		<scroll-view scroll-x class="border-right" style="width: 70%;">
			<view class="d-table border">
				<view class="d-tr" v-for="i in 4" :key="i">
					<view class="d-th border-top" style="width:124upx">李四</view>
					<view class="d-th border-top border-left" style="width:124upx">王五</view>
					<view class="d-th border-top border-left" style="width:124upx">王五</view>
					<view class="d-th border-top border-left" style="width:124upx">王五</view>
					<view class="d-th border-top border-left" style="width:124upx">王五</view>
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
