<template>
	<div class="item leadItem">
		<div class="title">用户中心</div>
		<ul class="ul">
			<li class="li" :style="{background:basecolor0}" @click="menu('1')">首页</li>
			<li class="li" :style="{background:basecolor1}" @click="menu('2')">账号信息</li>
			<li class="li" :style="{background:basecolor2}" @click="menu('3')">个人信息</li>
			<li class="li" :style="{background:basecolor3}" @click="menu('4')">我的作品</li>
			<li class="li" :style="{background:basecolor4}" @click="menu('5')">上传视频</li>
			<li class="li" :style="{background:basecolor5}" @click="menu('6')">我的收藏</li>
			<li class="li" :style="{background:basecolor6}" @click="menu('7')">历史记录</li>
		</ul>
	</div>
</template>

<script>
	import Msg from './msg.js'
	export default{
		data(){
			return{
				basecolor0:'lightblue',
				basecolor1:'',
				basecolor2:'',
				basecolor3:'',
				basecolor4:'',
				basecolor5:'',
				basecolor6:'',
				message:1
			}
		},
		methods:{
			menu(message1){
				console.log(message1)
				// this.$emit("parentEvent",message1)
				Msg.$emit("val",message1)
			}
		}
	}
</script>

<style>
	*{
		margin:0;
		padding:0;
	}
	.title{
		height: 40px;
		line-height: 40px;
		text-align: center;
	}
	.li{
		margin: 2px auto;
		width: 200px;
		height: 60px;
		list-style: none;
		background: navajowhite;
		line-height: 60px;
		text-align: center;
	}
</style>
