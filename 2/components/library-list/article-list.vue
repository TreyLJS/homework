<template>
	<div class="article-list clearfix">
		<nuxt-link to="/library/detail/article1" class="article-list__container clearfix">
			<h3 class="article-list__title"><strong>聚醚硅油</strong>_化妆品硅油_201甲基<strong>硅油</strong></h3>
			 <img class="article-list__pic" src="" alt="">
			<p class="article-list__text">目前使用即热式电热水器、快速电热水器的使用安全问题显得尤为突出。而其核心部件——发热体的安全性能的优劣与否，更是这两者安全与否的决定性因素。一、安全放在第使用即热式电热水器安全最重要！目...</p>
		</nuxt-link>
	</div>
</template>

<script>
	export default {

	}
</script>

<style scoped>
	.article-list {
		width: 100%;
		height: 100%;
		overflow: hidden;
	}
	.article-list__container {
		display: block;
		width: 827px;
		height: 137px;
		margin-bottom: 22px;
		text-decoration: none;
	}
	.article-list__title {
		width: 100%;
		height: 15px;
		font-size: 15px;
		line-height: 15px;
		color: #333333;
		margin-bottom: 12px;
	}
	.article-list__title strong {
		color: #ee5059;
	}
	.article-list__pic {
		width: 158px;
		height: 108px;
		float: left;
		border: 1px solid #eeeeee;
	}
	.article-list__text {
		float: left;
		display: block;
		margin-left: 19px;
		margin-top: 5px;
		font-size: 13px;
		line-height: 20px;
		width: 533px;
		height: 100%;
		color: #666666;
	}
</style>