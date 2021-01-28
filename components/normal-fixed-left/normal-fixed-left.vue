<template>
	<view class="container" style="display: flex;">
		<view class="d-table border" style="width: 30%;">
			<view class="d-tr" v-for="i in 4" :key="i"><view class="border-top" :class="i === 1 ? 'd-th' : 'd-td'">张三</view></view>
		</view>
		<scroll-view scroll-x class="border-right" style="width: 70%;">
			<view class="d-table border">
				<view class="d-tr" v-for="i in 4" :key="i">
					<view class="border-top" style="width:124upx" :class="i === 1 ? 'd-th' : 'd-td'">李四</view>
					<view class="border-top border-left" style="width:124upx" :class="i === 1 ? 'd-th' : 'd-td'">王五</view>
					<view class="border-top border-left" style="width:124upx" :class="i === 1 ? 'd-th' : 'd-td'">王五</view>
					<view class="border-top border-left" style="width:124upx" :class="i === 1 ? 'd-th' : 'd-td'">王五</view>
					<view class="border-top border-left" style="width:124upx" :class="i === 1 ? 'd-th' : 'd-td'">王五</view>
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
