<template>
	<div class="article-others clearfix">
		<div class="article-others__container clearfix">
			<h4 class="article-others__title clearfix">相关资讯</h4>
			<ul class="article-others__list clearfix">
				<li class="article-others__listitem"><nuxt-link to="" class="article-others__link">真空集热管利用热水上浮冷水下沉的原理</nuxt-link></li>
				<li class="article-others__listitem"><nuxt-link to="" class="article-others__link">真空集热管利用热水上浮冷水下沉的原理</nuxt-link></li>
				<li class="article-others__listitem"><nuxt-link to="" class="article-others__link">真空集热管利用热水上浮冷水下沉的原理</nuxt-link></li>
				<li class="article-others__listitem"><nuxt-link to="" class="article-others__link">真空集热管利用热水上浮冷水下沉的原理</nuxt-link></li>
				<li class="article-others__listitem"><nuxt-link to="" class="article-others__link">真空集热管利用热水上浮冷水下沉的原理</nuxt-link></li>
			</ul>
			<ul class="article-others__list clearfix">
				<li class="article-others__listitem"><nuxt-link to="" class="article-others__link">真空集热管利用热水上浮冷水下沉的原理</nuxt-link></li>
				<li class="article-others__listitem"><nuxt-link to="" class="article-others__link">真空集热管利用热水上浮冷水下沉的原理</nuxt-link></li>
				<li class="article-others__listitem"><nuxt-link to="" class="article-others__link">真空集热管利用热水上浮冷水下沉的原理</nuxt-link></li>
				<li class="article-others__listitem"><nuxt-link to="" class="article-others__link">真空集热管利用热水上浮冷水下沉的原理</nuxt-link></li>
				<li class="article-others__listitem"><nuxt-link to="" class="article-others__link">真空集热管利用热水上浮冷水下沉的原理真空集热管利用热水上浮冷水下沉的原理</nuxt-link></li>
			</ul>
		</div>
	</div>
</template>


<script>
	export default {

	}
</script>


<style scoped>
	*{
		margin: 0;
		padding: 0;
		list-style: none;
		text-decoration: none;
	}
	.clearfix::after {
		content: '';
		display: block;
		clear: both;

	}
	.article-others {
		width: 100%;
		height: 100%;
		overflow: hidden;
	}
	.article-others__container {
		width: 100%;
		height: 100%;
	}
	.article-others__title {
		display: block;
		padding-left: 30px;
		font-size: 15px;
		color: #333333;
		line-height: 15px;
		margin-bottom: 21px;
	}
	.article-others__list {
		width: 430px;
		float: left;
	}
	.article-others__listitem {
		height: 14px;
		margin-bottom: 11px;
	}
	.article-others__link {
		display: block;
		width: 430px;
		font-size: 14px;
		line-height: 14px;
		color: #333333;
		padding-left: 30px;
		background: url(~/assets/images/others_circle.png) 16px center no-repeat;
		overflow: hidden;
	    text-overflow: ellipsis;
	    white-space: nowrap;
	}
</style>