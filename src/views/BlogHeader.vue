<template>
	<nav>
		<ul>
			<li>
				<router-link to="/showblog" >博客</router-link>
				<router-link to="/addblog" >写博客</router-link>
			</li>
		</ul>
	</nav>
</template>

<script>
	export default {
		name: "BlogHeader"
	}
</script>

<style scoped>
	ul{
		list-style-type: none;
		text-align: center;
		margin: 0;
	}
	li{
		display: inline-block;
		margin: 0 10px;
	}
	a{
		text-decoration: none;
		color: #fff;
		padding: 12px;
		border-radius: 5px;
	}
	nav{
		background-color: crimson;
		padding: 30px 0;
		margin-bottom: 40px;
	}
	.router-link-active{
		background-color: rgba(255,255,255,0.8);
		color: #444;
	}
</style>