<template>
	<div class="wiki-dictionary clearfix">
		<top-diclist></top-diclist>
		<div class="wiki-dictionary__container clearfix">
			<div class="wiki-dictionary__content">
				<ul>
					<li><dictionary-list></dictionary-list></li>
					<li><dictionary-list></dictionary-list></li>
					<li><dictionary-list></dictionary-list></li>
					<li><dictionary-list></dictionary-list></li>
					<li><dictionary-list></dictionary-list></li>
					<li><dictionary-list></dictionary-list></li>
				</ul>
			</div>
			<div class="wiki-dictionary__sidebar">
				
			</div>
		</div>
	</div>
</template>

<script>
import DictionaryList from '~/components/dictionary-list/dictionary-list.vue'
import TopDiclist from '~/components/common/top-diclist.vue'

	export default {
		components : {
			DictionaryList,
			TopDiclist
		}
	}
</script>


<style>
	*{
		margin: 0;
		padding: 0;
		list-style: none;
	}
	.wiki-dictionary {
		width: 100%;
		height: 100%;
		overflow: hidden;
	}
	.wiki-dictionary__container {
		width: 1200px;
		height: 1158px;
		/*padding-top: 25px;*/
		/*background: #eee;*/
		margin: 25px auto 0;
	}
	.wiki-dictionary__content {
		width: 927px;
		height: 100%;
		/*background: green;*/
		border-right: 1px solid red;
		float: left;
	}
	.wiki-dictionary__sidebar {
		width: 272px;
		height: 100%;
		float: left;
		background: skyblue;
	}
</style>