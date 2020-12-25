<template>
	<div>
		<Header></Header>
		<div class="video">
			<Video></Video>
		</div>
		<div class="authorAbout">
			<Author></Author>
		</div>
		<div class="videoComment">
			<Comment></Comment>
		</div>
	</div>
</template>

<script>
	import Header from '../components/Header.vue'
	import Video from '../components/Play/Video.vue'
	import Comment from '../components/Play/Comment.vue'
	import Author from '../components/Play/Author.vue'
	export default{
		components:{
			Header,
			Video,
			Comment,
			Author
		}
	}
</script>

<style>
	*{
		padding: 0;
		margin: 0;
	}
	.video,.videoComment{
		float: left;
		margin-left: 200px;
		margin-top: 30px;
	}
	.authorAbout{
		float: right;
		margin-right: 150px;
		margin-top: 30px;
		height: 200px;
		width: 350px;
		background: #0056B3;
	}
</style>
