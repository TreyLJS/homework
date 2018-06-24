<template>
	<div class="dictionary-list clearfix">
		<div class="dictionary-list__container clearfix">
			<nuxt-link to=""><img class="dictionary-list__pic" src="" alt=""></nuxt-link>
			<div class="dictionary-list__content">
				<h3 class="dictionary-list__title"><nuxt-link to="" class="dictionary-list__name">甲醇</nuxt-link></h3>
				<p class="dictionary-list__text clearfix">
					<span>分子式：CH2O</span>
					<span>分子量：30.03</span>
					<span>CAS号：50-00-0</span>
				</p>
			</div>
			
		</div>
	</div>
</template>

<script>
	export default {

	}
</script>

<style scoped>
	.dictionary-list {
		width: 100%;
		height: 100%;
		overflow: hidden;
	}
	.dictionary-list__container {
		width: 899px;
		height: 179px;
		border-bottom: 2px solid #ebebeb;
		margin-bottom: 19px;
		overflow: hidden;
	}
	.dictionary-list__pic {
		display: block;
		width: 158px;
		height: 158px;
		float: left;
		border: 1px solid #d2d2d2;
	}
	.dictionary-list__content {
		display: block;
		float: left;
		width: 690px;
		margin-left: 49px;
	}
	.dictionary-list__title {
		display: block;
		font-size: 18px;
		line-height: 76px;
		color: #333333;
		margin-top: 21px;
	}
	.dictionary-list__name {
		color: #333333;
	}
	.dictionary-list__text {
		display: block;
	}
	.dictionary-list__text span {
		font-size: 12px;
		line-height: 20px;
		color: #666666;
		margin-right: 130px;
	}
</style>