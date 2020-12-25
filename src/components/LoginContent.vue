<template>
	<div id="container">
		<h1 align="center">用户登录</h1>
		<form class="form">
		  <div class="form-group2">
		    <label for="username">username</label>
		    <input type="text" class="form-control" id="username" placeholder="username" v-model="username">
		  </div>
		  <div class="form-group2">
		    <label for="password">Password</label>
		    <input type="password" class="form-control" id="password" placeholder="password" v-model="password">
		  </div>
		  <div class="form-group2" align="center">
			   <button type="submit" class="btn btn-light" style="background-color: #17A2B8;width: 200px;">登&nbsp;&nbsp;&nbsp;&nbsp;录</button>
		  </div>
		</form>
		
	</div>
</template>

<script>
	export default{
		data(){
			return {
				username:"",
				password:"",
			}
		}
	}
</script>

<style type="text/css">
		#container{
			display: grid;
			place-items: center;
			padding: 1.25rem;
			margin-top: 100px;
		}
		.form-group2{
			width: 400px;
			padding: 10px; 
			margin-top: 30px;
		}
		.form-control{
			width: 400px;
			height: 40px;
		}
		#button{
			width: 200px;
		}
	</style>
