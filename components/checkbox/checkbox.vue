<template>
	<view class="container">
		<view class="d-table border">
			<view class="d-tr" v-for="i in 5" :key="i">
				<view class="d-th border-top">
					<checkbox-group name="">
						<label>
							<checkbox value="1" /><text></text>
						</label>
					</checkbox-group>
				</view>
				<view class="d-th border-top border-left">张三</view>
				<view class="d-th border-top border-left">李四</view>
				<view class="d-th border-top border-left">王五</view>
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
		checkbox{
			transform: scale(0.8);
		}
	}
</style>
