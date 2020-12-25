<template>
	<div>
		<div class="up-container">
		<form>
			<div class="form-group">
			    <label for="exampleFormControlSelect1">你的视频类型</label>
			    <select class="form-control" id="exampleFormControlSelect1">
			      <option>1</option>
			      <option>2</option>
			      <option>3</option>
			      <option>4</option>
			      <option>5</option>
			    </select>
			</div>
			<div class="form-group">
			    <label for="exampleFormControlTextarea1">视频介绍</label>
			    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
			 </div>
			<div class="form-group">
				<label for="exampleFormControlFile1">请添加你要上传的视频</label>
				<input type="file" class="form-control-file" id="exampleFormControlFile1">
			</div>
			<div class="form-group" align="center">
				<button type="submit" class="btn btn-light" style="background-color: #2D93CA; width: 200px;">注&nbsp;&nbsp;&nbsp;&nbsp;册</button>
			</div>
		</form>
	</div>
	</div>
	
</template>

<script>
	
</script>

<style>
	*{
		margin: 0;
		padding: 0;
	}
	.up-container{
		display: grid;
		margin: 0 auto;
		place-items: center;
	}
	.form-group{
		padding: 12px;
		width: 400px;
	}
</style>
