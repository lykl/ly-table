<template>
	<view class="container">
		<view class="d-table">
			<view class="d-tr">
				<view class="d-td">
					<view class="d-table">
						<view class="d-tr">
							<view class="d-th border-top border-left border-bottom">张三</view>
							<view class="d-th border-top border-left border-bottom">李四</view>
							<view class="d-th border-top border-left border-right border-bottom">王五</view>
						</view>
					</view>
				</view>
			</view>
			<view class="d-tr">
				<view class="d-td">
					<view class="d-table">
						<view class="d-tr">
							<view class="d-td border-left border-bottom" style="width:66.6%">
								张三
							</view>
							<view class="d-td border-left border-right border-bottom">
								王五
							</view>
						</view>
					</view>
				</view>
			</view>
			<view class="d-tr">
				<view class="d-td">
					<view class="d-table">
						<view class="d-tr">
							<view class="d-td border-left border-bottom">张三</view>
							<view class="d-td border-left border-bottom">李四</view>
							<view class="d-td border-left border-bottom border-right">王五</view>
						</view>
					</view>
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
	.container{
		padding: 10rpx;
	}
</style>
