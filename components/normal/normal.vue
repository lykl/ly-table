<template>
	<view class="container">
		<view class="div-table">
			<view class="div-table-thead">
				<view class="div-table-tr">
					<view class="div-table-th border-top">张三</view>
					<view class="div-table-th border-top">李四</view>
					<view class="div-table-th border-top">王五</view>
				</view>
			</view>
			<view class="div-table-tbody">
				<view class="div-table-tr">
					<view class="div-table-td border-top">张三</view>
					<view class="div-table-td border-top">李四</view>
					<view class="div-table-td border-top">王五</view>
				</view>
			</view>
			<view class="div-table-tfoot">
				<view class="div-table-tr">
					<view class="div-table-td border-top border-bottom">张三</view>
					<view class="div-table-td border-top border-bottom">李四</view>
					<view class="div-table-td border-top border-bottom">王五</view>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="scss">
	@import url("../../common/common.css");
	.div-table{
		background-color: white;
	}
</style>
