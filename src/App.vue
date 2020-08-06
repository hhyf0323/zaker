<template>
	<div id="app">
		<div id="nav">
			<!-- <div><van-icon name="chat" size="2rem" color="#666"/><br><router-link to="/">资讯</router-link></div>
			<div><van-icon name="play" size="2rem" color="#666"/><br><router-link to="/about">视频</router-link></div>
			<div><van-icon name="browsing-history" color="#666" size="2rem"/><br><router-link to="/bottom">刷新</router-link></div>
			<div><van-icon name="manager" color="#666" size="2rem"/><br><router-link to="/mine">我的</router-link></div> -->
			<van-tabbar v-model="active">
				<van-tabbar-item icon="chat" ><router-link to="/">资讯</router-link></van-tabbar-item>
				<van-tabbar-item icon="play"><router-link to="/about">视频</router-link></van-tabbar-item>
				<van-tabbar-item icon="browsing-history"><router-link to="/bottom">发现</router-link></van-tabbar-item>
				<van-tabbar-item icon="manager"><router-link to="/mine">我的</router-link></van-tabbar-item>
			</van-tabbar>
		</div>
		<router-view />
	</div>
</template>

<style scoped>
	#app {
		background: #ffffff;
	}

	#nav {
		width: 100%;
		position: fixed;
		bottom: 0;
		padding-bottom: .5rem;
		display: flex;
		z-index: 99;
		background: #ffffff;
	}

	#nav>div {
		flex: 1;
		text-align: center;
	}

	#nav>div a {
		font-size: 1.3rem;
		color: #666;
	}
</style>
<script>
	export default {
		data() {
			return {
				active: 0,
			};
		},
	};
</script>
