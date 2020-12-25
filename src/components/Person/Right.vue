<template>
	<div>
		<div v-if="number==1">
			
		</div>
		<div v-if="number==2">
			
		</div>
		<div v-if="number==3">
			
		</div>
		<div v-if="number==4">
			
		</div>
		<div v-if="number==5">
			<Up></Up>
		</div>
		<div v-if="number==6">
			
		</div>
		<div v-if="number==6">
			
		</div>
	</div>
</template>

<script>
	import Msg from './msg.js'
	import Up from '../Up/Up.vue'
	export default{
		components:{
			Up
		},
		// props:['message'],
		data(){
			return {
				number:1
			}
		},
		created(){
			this.getMsg()
		},
		methods:{
			getMsg(){
				var _this = this
				Msg.$on("val",(msg)=>{
					console.log(msg)
					_this.number=msg
				})
			}
		}
		
		
	}
</script>

<style>
</style>
