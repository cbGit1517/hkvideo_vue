<template>
	<div>
		<p class="videoTitle">title</p>
		<p class="videoAbout">
			test
		</p>
		<video width="800" height="500" controls="controls" autoplay="autoplay">
			<source src="http://vjs.zencdn.net/v/oceans.mp4" type="video/mp4">
		</video>
	</div>
</template>

<script>
</script>

<style>
	*{
		padding: 0;
		margin: 0;
	}
	.videoTitle{
		font-size: 18px;
		margin-bottom: 5px;
	}
	.videoAbout{
		font-size: 12px;
		margin-bottom: 5px;
		margin-top: 0;
	}
</style>
