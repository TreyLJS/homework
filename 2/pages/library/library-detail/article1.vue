<template>
	<div class="library-article clearfix">
		<top-libdetail></top-libdetail>
		<div class="library-article__container clearfix">
			<div class="library-article__content clearfix">
				<div class="library-article__article clearfix">
					<h3 class="library-article__title">太阳能热水器原理图及优缺点</h3>
					<span class="library-article__description">发布时间：2018年05月04日 浏览：30 来源：<nuxt-link to="" class="library-article__from">www.sic.wik</nuxt-link></span>
					<div class="library-article__share clearfix">
						<span>分享到：</span>
						<nuxt-link to="" class="library-article__shareto"><img src="~/assets/images/qqroom.png" alt=""></nuxt-link>
						<nuxt-link to="" class="library-article__shareto"><img src="~/assets/images/weibo.png" alt=""></nuxt-link>
						<nuxt-link to="" class="library-article__shareto"><img src="~/assets/images/qq.png" alt=""></nuxt-link>
						<nuxt-link to="" class="library-article__shareto"><img src="~/assets/images/wechat.png" alt=""></nuxt-link>
					</div>
					<div class="library-article__text">
						<p>太阳能热水器是将太阳光能转化为热能的加热装置，将水从低温加热到高温，以满足人们在生活、生产中的热水使用。太阳能热水器按结构形式分为真空管式太阳能热水器和平板式太阳能热水器，主要以真空管式太阳能热水器为主，占据国内95%的市场份额。真空管式家用太阳能热水器是有集热管、储水箱及支架等相关零配件组成，把太阳能转换成热能主要依靠真空集热管，真空集热管利用热水上浮冷水下沉的原理，是生产微循环而得到所需热水。</p>
						<span>太阳能热水器原理图</span>
						<img src="" alt="">
					</div>

				</div>
				<div class="library-article__more clearfix">
					<div class="library-article__prev library-article__morepage">
						<span>阅读上一篇</span>
						<nuxt-link to="" class="library-article__particle">
							<h4>光热转换材料及太阳能热水器的现</h4>
							<span>太阳能热水器是将太阳光能转换为热能的加热装置，将水从低位加热到高温，以满足人们在生活、生产中的热水使用。太阳能热水器按结构形式</span>
						</nuxt-link>
					</div>
					<div class="library-article__next library-article__morepage">
						<span>阅读上一篇</span>
						<nuxt-link to="" class="library-article__particle">
							<h4>真空管式家用太阳能热水器是由集热管</h4>
							<span>太阳能热水器是将太阳光能转化为热能的加热装置，将水从低温加热到高温，以满足人们在生活、生产中的热水使用。太阳能热水器按结构形式分为真空管式太阳能热水器和平板式太阳能热水</span>
						</nuxt-link>
					</div>
					<div></div>
				</div>
				<div class="library-article__others clearfix"><article-others></article-others></div>
			</div>
			<div class="library-article__sidebar clearfix"></div>
		</div>
		
	</div>
</template>

<script>
import TopLibdetail from '~/components/common/top-libdetail.vue'
import ArticleOthers from '~/components/article-detail/article-others.vue'



	export default {
		components : {
			TopLibdetail,
			ArticleOthers
		}
	}
</script>


<style>
	*{
		margin: 0;
		padding: 0;
		list-style: none;
	}
	.clearfix::after {
		content: '';
		display: block;
		clear: both;
	}
	.library-article {
		width: 100%;
		height: 100%;
		overflow: hidden;
	}
	.library-article__container {
		width: 1200px;
		height: 100%;
		margin: 25px auto 0;
	}
	.library-article__content {
		width: 948px;
		height: 100%;
		float: left;
	}
	.library-article__article {
		width: 769px;
		height: 100%;
		margin-left: 30px;
		margin-right: 149px;
		padding-bottom: 30px;
		border-bottom: 1px solid #eeeeee;
	}
	.library-article__title {
		font-size: 25px;
		line-height: 49px;
		color: #000000;
		text-align: center;
	}
	.library-article__description {
		display: block;
		font-size: 14px;
		line-height: 27px;
		color: #333333;
		text-align: center;
		word-spacing: 14px;
	}
	.library-article__from {
		color: #1aa5c3;
	}
	.library-article__share {
		line-height: 27px;
		padding: 23px 277px;
	}
	.library-article__share span {
		font-size: 14px;
		line-height: 27px;
		display: inline-block;
		float: left;
		color: #000000;
	}
	.library-article__shareto {
		display: inline-block;
		float: left;
		width: 27px;
		height: 27px;
		line-height: 27px;
		margin-right: 8px;
	}
	.library-article__shareto img {
		width: 27px;
		height: 27px;
	
	}
	.library-article__share span {
		margin-right: 15px;
	}
	.library-article__text {
		width: 100%;
		height: 100%;
		padding-top: 3px;

	}
	.library-article__text p {
		font-size: 14px;
		line-height: 25px;
		color: #333333;
		text-indent: 2em;
	}
	.library-article__text span {
		display: block;
		margin-top: 12px;
		line-height: 64px;
		height: 64px;
		line-height: 16px;
		text-indent: 2em;
	}
	.library-article__text img {
		display: block;
		width: 598px;
		height: 398px;
		border: 1px solid #eeeeee;
		margin: 0 auto;
	}
	.library-article__more {
		width: 100%;
		height: 154px;
		padding-top: 20px;
	}
	.library-article__morepage{
		width: 400px;
		margin-left: 30px;
		height: 154px;
		float: left;
	}
	.library-article__morepage span {
		font-size: 16px;
		line-height: 42px;
		color: #666666;
		display: block;
	}
	.library-article__particle h4 {
		font-size: 15px;
		line-height: 27px;
		color: #333333;
		width: 400px;
		overflow: hidden;
	    text-overflow: ellipsis;
	    white-space: nowrap;
	}
	.library-article__particle span {
		font-size: 12px;
		line-height: 20px;
		color: #888888;
	}
	.library-article__sidebar {
		width: 252px;
		height: 1000px;
		float: left;
		background: green;
	}
	.library-article__others{

	}
</style>