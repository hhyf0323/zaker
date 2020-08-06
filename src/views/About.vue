<template>
	<div class="about">
		<van-tabs v-model="activeName">
			<van-tab title="视频" name="a">
				<div class="ma">
					<div class="top">
						<div class="join">可能是国内最晚上牌的EVO 9，车主却买来家<br />用代步</div>
						<div class="flex">
							<div><img src="../assets/48.png" class="img"></div>
							<div class="gai">改装车</div>
						</div>
					<div><img src="../assets/49.png" class="lun"/></div>
					</div>
					<div class="top">
						<div class="join">试驾标致2008：这款设计出众操控优秀的小车<br />让你们久等了</div>
						<div class="flex">
							<div><img src="../assets/48.png" class="img"></div>
							<div class="gai">新车评网</div>
						</div>
					<div><img src="../assets/50.png" class="lun"/></div>
					</div>
					<div class="top">
						<div class="join">光电测试：气温最高39℃，特斯拉Model 3实<br />际能跑多远？</div>
						<div class="flex">
							<div><img src="../assets/48.png" class="img"></div>
							<div class="gai">新车评网</div>
						</div>
					<div><img src="../assets/51.png" class="lun"/></div>
					</div>
					<div class="top">
						<div class="join">炸银鳕鱼块，另一种口感的美味</div>
						<div class="flex">
							<div><img src="../assets/55.png" class="img"></div>
							<div class="gai">淳味坊</div>
						</div>
					<div><img src="../assets/52.png" class="lun"/></div>
					</div>
					<div class="top">
						<div class="join">中国最长玻璃吊桥，张家界的都没法比，还拿<br/>下了世界记录!</div>
						<div class="flex">
							<div><img src="../assets/55.png" class="img"></div>
							<div class="gai">数码测评</div>
						</div>
					<div><img src="../assets/53.png" class="lun"/></div>
					</div>
					<div class="top">
						<div class="join">如果《万物都有生命》世界该会多可爱！</div>
						<div class="flex">
							<div><img src="../assets/55.png" class="img"></div>
							<div class="gai">V电影</div>
						</div>
					<div><img src="../assets/54.png" class="lun"/></div>
					</div>
				</div>
			</van-tab>
			<van-tab title="直播" name="b">内容 2</van-tab>

		</van-tabs>
	</div>
</template>
<style scoped>
	.ma {
		margin-left: 2.2rem;
	}

	.top {
		margin-top: 2rem;
	}

	.join {
		margin-top: 1rem;
		font-size: 1.5rem;
		font-weight: bold;
	}

	.flex {
		display: flex;
		margin-top: 1rem;
	}

	.img {
		width: 2.2rem;
	}

	.gai {
		margin-left: 1rem;
		line-height: 2.5rem;
	}
	.lun {
		width: 94%;
	}
</style>
<script>
	export default {
		data() {
			return {
				activeName: 'a',
			};
		},
	};
</script>
