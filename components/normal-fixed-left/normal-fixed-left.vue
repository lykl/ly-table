<template>
	<view class="container" style="display: flex;">
		<view class="d-table" style="width: 30%;">
			<view class="d-tr" v-for="i in 4" :key="i"><view :class="i === 1 ? 'd-th' : 'd-td'">张三</view></view>
		</view>
		<scroll-view scroll-x class="border-right" style="width: 70%;">
			<view class="d-table scroll-x">
				<view class="d-tr" v-for="i in 4" :key="i">
					<view style="width:124rpx" :class="i === 1 ? 'd-th' : 'd-td'">李四</view>
					<view style="width:124rpx" :class="i === 1 ? 'd-th' : 'd-td'">王五</view>
					<view style="width:124rpx" :class="i === 1 ? 'd-th' : 'd-td'">王五</view>
					<view style="width:124rpx" :class="i === 1 ? 'd-th' : 'd-td'">王五</view>
					<view style="width:124rpx" :class="i === 1 ? 'd-th' : 'd-td'">王五</view>
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
	.d-table.scroll-x {
		.d-td,
		.d-th {
			&:first-child {
				border-left: 0;
			}
		}
	}
}
</style>
