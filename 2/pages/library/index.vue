<template>
	<div class="wiki-library clearfix">
		<top-liblist></top-liblist>
		<div class="wiki-library__container clearfix">
			<div class="wiki-library__content">
				<ul>
					<li><article-list></article-list></li>
					<li><article-list></article-list></li>
					<li><article-list></article-list></li>
					<li><article-list></article-list></li>
					<li><article-list></article-list></li>
					<li><article-list></article-list></li>
				</ul>
			</div>
			<div class="wiki-library__sidebar">
				
			</div>
		</div>
	</div>
</template>

<script>
import ArticleList from '~/components/library-list/article-list.vue'
import TopLiblist from '~/components/common/top-liblist.vue'

	export default {
		components : {
			ArticleList,
			TopLiblist
		}
	}
</script>


<style>
	*{
		margin: 0;
		padding: 0;
		list-style: none;
	}
	.wiki-library {
		width: 100%;
		height: 100%;
		overflow: hidden;
	}
	.wiki-library__container {
		width: 1200px;
		height: 1158px;
		/*padding-top: 25px;*/
		/*background: #eee;*/
		margin: 25px auto 0;
	}
	.wiki-library__content {
		width: 927px;
		height: 100%;
		/*background: green;*/
		border-right: 1px solid red;
		float: left;
	}
	.wiki-library__sidebar {
		width: 272px;
		height: 100%;
		float: left;
		background: skyblue;
	}
</style>