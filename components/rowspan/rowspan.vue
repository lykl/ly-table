<template>
	<view class="container">
		<view class="d-table border">
			<view class="d-tr">
				<view class="d-th border-top">张三</view>
				<view class="d-th border-top border-left">李四</view>
				<view class="d-th border-top border-left border-right">王五</view>
			</view>
			<view class="d-tr">
				<view class="d-td">
					<view class="d-table">
						<view class="d-tr">
							<view class="d-td border-left">张三</view>
						</view>
					</view>
				</view>
				<view class="d-td">
					<view class="d-table">
						<view class="d-tr">
							<view class="d-td border-top border-left">李四</view>
						</view>
						<view class="d-tr">
							<view class="d-td border-top border-left">李四</view>
						</view>
						<view class="d-tr">
							<view class="d-td border-top border-left">李四</view>
						</view>
					</view>
				</view>
				<view class="d-td">
					<view class="d-table">
						<view class="d-tr">
							<view class="d-td border-top border-left border-right">王五</view>
						</view>
						<view class="d-tr">
							<view class="d-td border-top border-left border-right">王五</view>
						</view>
						<view class="d-tr">
							<view class="d-td border-top border-left border-right">王五</view>
						</view>
					</view>
				</view>
			</view>
			<view class="d-tr">
				<view class="d-td border-top">张三</view>
				<view class="d-td border-top border-left">李四</view>
				<view class="d-td border-top border-left">王五</view>
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
	.container{
		padding: 10rpx;
	}
</style>
