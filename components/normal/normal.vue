<template>
	<view class="container">
		<view class="d-table border" v-for="item in typeList" :key="item" :class="[item, 'margin-bottom-10']">
			<view class="d-thead">
				<view class="d-tr">
					<view class="d-th">张三</view>
					<view class="d-th border-left">李四</view>
					<view class="d-th border-left">王五</view>
				</view>
			</view>
			<view class="d-tbody">
				<view class="d-tr">
					<view class="d-td border-top">张三</view>
					<view class="d-td border-left border-top">李四</view>
					<view class="d-td border-left border-top">王五</view>
				</view>
			</view>
			<view class="d-tfoot">
				<view class="d-tr">
					<view class="d-td border-top">张三</view>
					<view class="d-td border-left border-top">李四</view>
					<view class="d-td border-left border-top">王五</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
export default {
	data() {
		return {
			typeList: ['normal', 'primary', 'success', 'warning', 'danger', 'info','gray']
		};
	}
};
</script>

<style lang="scss">
.container {
	padding: 10rpx;
}
</style>
