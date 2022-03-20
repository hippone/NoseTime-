<template>
	<view>
		<view class="u-demo-block__content">
			<view class="u-page__tag-item">
				<u-search
					placeholder="香水时代小程序毕设"
					disabled
					:click="goSearch"
					:show-action="false"
				></u-search>
			</view>
		</view>
		 <!-- 轮播图 -->
		<view>
			<u-swiper
					:list="list3"
					indicator
					indicatorMode="line"
					circular
			></u-swiper>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				 list3: [
							'https://cdn.uviewui.com/uview/swiper/swiper3.png',
							'https://cdn.uviewui.com/uview/swiper/swiper2.png',
							'https://cdn.uviewui.com/uview/swiper/swiper1.png',
						],
			}
		},
		onLoad() {

		},
		methods: {
			goSearch(){
				
			}
		}
	}
</script>

<style lang="scss">
	.u-demo-block__content{
		margin:10rpx 20rpx;
	}
</style>
