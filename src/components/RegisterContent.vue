<template>
	<div id="container1">
		<h1 align="center">用户注册</h1>
		<form class="form" action="/register" method="post">
		  <div class="form-group1">
		    <label for="username">username</label>
		    <input type="text" class="form-control1" id="username" placeholder="username" v-model="username">
		  </div>
		  <div class="form-group1">
		    <label for="password1">Password</label>
		    <input type="password" class="form-control1" id="password1" placeholder="password" v-model="password1">
		  </div>
		  <div class="form-group1">
		    <label for="password2">Confirm Password</label>
		    <input type="password" class="form-control1" id="password2" placeholder="confirm password" v-model="password2"><span class="error">{{message}}</span>
		  </div>
		  <div class="form-group1">
		    <label for="phone">phone</label>
		    <input type="text" class="form-control1" id="phone" placeholder="phone" v-model="phone">
		  </div>
		  <div class="form-group1" align="center">
			   <button type="submit" class="btn btn-light" style="background-color: #2D93CA; width: 200px;">注&nbsp;&nbsp;&nbsp;&nbsp;册</button>
		  </div>
		</form>
		
	</div>
</template>

<script>
	export default{
		data(){
			return {
				username:"",
				password1:"",
				password2:"",
				phone:"",
				message:""
			}
		}
	}
</script>

<style type="text/css">
		#container1{
			margin-top: 20px;
			display: grid;
			place-items: center;
			padding: 1.25rem;
		}
		.form-group1{
			margin: 1rem auto;
			padding: 10px; 
		}
		.form{
			width: 400px;
		}
		.form-control1{
			width: 400px;
			height: 40px;
			color: #0056B3;
		}
		.error{
			background-color: #009F95;
			font-size: 12px;
		}
</style>
