<template>
	<view class="container">
		<view class="div-table">
			<view class="div-table-thead">
				<view class="div-table-tr">
					<view class="div-table-td border-top">
						<view class="div-table">
							<view class="div-table-tr">
								<view class="div-table-th">张三</view>
								<view class="div-table-th">李四</view>
								<view class="div-table-th">王五</view>
							</view>
						</view>
					</view>
				</view>
			</view>
			<view class="div-table-tbody">
				<view class="div-table-tr">
					<view class="div-table-td">
						<view class="div-table">
							<view class="div-table-tr">
								<view class="div-table-td border-top" style="width:66.6%">
									<view class="div-table">
										<view class="div-table-tr">
											<view class="div-table-td">张三</view>
										</view>
									</view>
								</view>
								<view class="div-table-td border-top">
									<view class="div-table">
										<view class="div-table-tr">
											<view class="div-table-td">王五</view>
										</view>
									</view>
								</view>
							</view>
						</view>
					</view>
				</view>
			</view>
			<view class="div-table-tfoot">
				<view class="div-table-tr">
					<view class="div-table-td border-top border-bottom">
						<view class="div-table">
							<view class="div-table-tr">
								<view class="div-table-td">张三</view>
								<view class="div-table-td">李四</view>
								<view class="div-table-td">王五</view>
							</view>
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
	@import url("../../common/common.css");
	.div-table{
		background-color: white;
	}
</style>
