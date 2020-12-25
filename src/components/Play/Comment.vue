<template>
	<ul class="ul-comment">
		<li v-for="i in 10" class="li-comment">
			<div class="li-comment-img">
				<img src="../../assets/logo.png" alt="Cinque Terre" class="img-circle" width="48" height="48">
				<p>z这是用户名</p>
			</div>
			<div class="li-comment-div">
				<p class="li-comment-content">这是一条评论</p>
				<p class="li-comment-about">2020-12-25</p>
				<hr>
			</div>
		</li>
	</ul>
</template>

<script>
</script>

<style>
	*{
		margin: 0;
		padding: 0;
	}
	.li-comment-img p{
		font-size: 12px;
	}
	.li-comment{
		list-style: none;
		width: 800px;
		/* background: #8FD19E; */
		line-height: normal;
	}
	.li-comment-div{
		
	}
	.li-comment-content{
		font-size: 18px;
	}
	.li-comment-about{
		font-size: 12px;
	}
</style>
