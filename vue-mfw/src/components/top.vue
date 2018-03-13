<template>
	<div id="com_top">
		<h1 id="logo">
			<img src="../../static/img/logo-new204.png"/>
		</h1>
		<p id="h_r">
			<a href="" id="a1">官网首页</a>
			<a href="" id="a2"></a>
		</p>
	</div>
</template>

<script>
	export default {
		name:"top"
	}
</script>

<style scoped>
	#com_top{
		padding: .15rem;
		overflow: hidden;
		border-bottom: .01rem solid #e3e3e3;
		height: 0.55rem;
	}
	#logo{
		float: left;
	}
	#logo img{
		width: 1.05rem;
		height: .28rem;
	}
	#h_r{
		float: right;
	}
	#h_r a{
		display: inline-block;		
	}
	#h_r #a1{
		color: #ff9d00;
		padding: 0 .1rem;
		/*border-right: .02rem solid #e6e3e3;*/
		float: left;
		height: .3rem;
		line-height: .3rem;
		margin-right: .1rem;
	}
	#h_r #a2{
		width: .3rem;
		height: .3rem;
		background:url(../../static/img/i_head5.png) 
		no-repeat -.1rem -.6rem;
		background-size: 1rem;
		float: left;
	}
</style>