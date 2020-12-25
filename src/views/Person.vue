<!-- 个人中心 -->
<template>
	<div>
		<Header></Header>
		<div class="left">
			<Left></Left>
		</div>
		<div class="right">
			<Right></Right>
		</div>
		
	</div>
	
</template>

<script>
	import Header from '../components/Header.vue'
	import Left from '../components/Person/Left.vue'
	import Right from '../components/Person/Right.vue'
	export default{
		components:{
			Header,
			Left,
			Right
		},
		data(){
			return{
				message:0,
			}
		},
		methods:{
			// myGetData(message){
			// 	this.message=message
			// }
		}
	}
</script>

<style>
	*{
		margin: 0;
		padding: 0;
	}
	.left,.right{
		float: left;
		margin-left: 120px;
		margin-top: 50px;
		height: 470px;
	}
	.right{
		background: #48B3F5;
		width: 800px;
	}
	.left{
		background: #48B3F5;
		width: 200px;
	}
</style>
