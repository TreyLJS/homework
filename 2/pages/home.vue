<template>
	<div class="sic-home">
		<div class="sic-home__container">
			<h1 class="sic-home__title">这是标题</h1>
		</div>
	</div>
</template>

<script>
	export default {

	}
</script>

<style>
@component-namespace sic {
	@b home {
		width: 100%;
		height: 100%;
		@e container {
			width: 1200px;
			height: 600px;
			background: #ccc;
			margin: 0 auto;
		}
	}
}
</style>