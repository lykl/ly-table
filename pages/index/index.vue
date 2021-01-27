<template>
	<view class="content" style="padding-bottom: 50rpx;">
		<text class="title">普通表格:</text>
		<normal></normal>
		<text class="title">含checkbox表格:</text>
		<checkboxTable></checkboxTable>
		<text class="title">头部固定表格:</text>
		<fixedHeader></fixedHeader>
		<text class="title">固定左边一列:</text>
		<fixedLeft></fixedLeft>
		<text class="title">合并行:</text>
		<rowspan></rowspan>
		<text class="title">合并列:</text>
		<colspan></colspan>
	</view>
</template>

<script>
	import normal from '@/components/normal/normal.vue'
	import checkboxTable from '@/components/checkbox/checkbox.vue'
	import fixedHeader from '@/components/normal-fixed-header/normal-fixed-header.vue'
	import fixedLeft from '@/components/normal-fixed-left/normal-fixed-left.vue'
	import rowspan from '@/components/rowspan/rowspan.vue'
	import colspan from '@/components/colspan/colspan.vue'
	export default {
		components:{
			normal,
			checkboxTable,
			fixedHeader,
			fixedLeft,
			rowspan,
			colspan
		},
		data() {
			return {
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.title{
		font-size: 32upx;
		margin-bottom: 10upx;
	}
</style>
