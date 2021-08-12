<template>
	<div class="header">
		<div class="header_text">
			{{title}}
		</div>
	</div>
</template>

<script>
	export default{
		name:"sheader",
		props:["title"]
	}
</script>

<style scoped>
	*{
		padding:0;
		margin: 0;
	}
	li{
		list-style: none;
	}
	a{
		text-decoration: none;
		font-style: normal;
	}
	input{
		outline: none;
	}
	
	.header{
		width: 100%;
		height: 1.3rem;
		background: #fca92d;
	}
	.header_text{
		color: #fff;
		font-size: 0.48rem;
		font-family: "微软雅黑";
		display: block;
		box-sizing: border-box;
		text-align: center;
		line-height: 1.3rem;
	}
</style>
