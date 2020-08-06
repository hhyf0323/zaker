<template>
	<div class="home">
		<van-tabs v-model="active">
			<van-tab title="热点">
				<div class="ma">
					<div class="life">马庄的小康生活</div>
					<div class="flex">
						<div class="yang">央视新闻客户端</div>
						<div class="zhi">置顶</div>
					</div>
					<div class="life2">习近平的深情牵挂：“安心水”怎润百姓心</div>
					<div class="flex">
						<div class="yang">人民网</div>
						<div class="zhi">置顶</div>
					</div>
					<div class="join">加强党的组织建设，把好选人用人关</div>
					<div class="qiu">求是网</div>
				</div>
				<div class="gray"></div>
				<div class="ma">
					<div><img src="../assets/15.png" class="day" /></div>
					<div class="top">
						<van-swipe @change="onChange">
							<van-swipe-item><img src="../assets/16.png" class="lun" /></van-swipe-item>
							<van-swipe-item><img src="../assets/17.png" class="lun" /></van-swipe-item>
							<van-swipe-item><img src="../assets/18.png" class="lun" /></van-swipe-item>
							<template #indicator>
								<div class="custom-indicator">
								</div>
							</template>
						</van-swipe>
					</div>
				</div>
				<div class="gray"></div>
				<div class="ma">
					<div class="join">天价账单曝光：他跑来新西兰枪杀51人，政府<br />每年却花$180万养他</div>
					<div class="qiu">发现新西兰 1小时前</div>
					<div><img src="../assets/19.png" class="lun" /></div>
					<div class="join">两小时看懂印象派！夜访敦煌千年绮华展！硬<br />核文化活动又上新啦~</div>
					<div class="qiu">稻草人旅行 3小时前</div>
					<div><img src="../assets/20.png" class="lun" /></div>

					<div class="join">马斯克称赞中国人民，建议其他企业少花点时<br />间在PPT上</div>
					<div class="qiu">IT之家 17评论</div>
					<div style="height: 5rem;"></div>
				</div>
			</van-tab>
			<van-tab title="订阅">
				<div>
					<van-swipe class="my-swipe" :autoplay="3000" indicator-color="white">
						<van-swipe-item><img src="../assets/21.png" class="lun2"></van-swipe-item>
						<van-swipe-item><img src="../assets/22.png" class="lun2"></van-swipe-item>
						<van-swipe-item><img src="../assets/23.png" class="lun2"></van-swipe-item>
						<van-swipe-item><img src="../assets/24.png" class="lun2"></van-swipe-item>
					</van-swipe>
				</div>
				<div class="line">
					<div class="tou">
						<div><img src="../assets/25.png" class="pic"></div>
						<div>头条新闻</div>
					</div>
					<div class="tou">
						<div><img src="../assets/26.png" class="pic"></div>
						<div>今日看点</div>
					</div>
					<div class="tou">
						<div><img src="../assets/27.png" class="pic"></div>
						<div>科技频道</div>
					</div>
				</div>
				<div class="line">
					<div class="tou">
						<div><img src="../assets/28.png" class="pic"></div>
						<div>娱乐八卦</div>
					</div>
					<div class="tou">
						<div><img src="../assets/29.png" class="pic"></div>
						<div>体育频道</div>
					</div>
					<div class="tou">
						<div><img src="../assets/30.png" class="pic"></div>
						<div>NBA</div>
					</div>
				</div>
				<div class="line">
					<div class="tou">
						<div><img src="../assets/31.png" class="pic"></div>
						<div>财经新闻</div>
					</div>
					<div class="tou">
						<div><img src="../assets/32.png" class="pic"></div>
						<div>汽车频道</div>
					</div>
					<div class="tou">
						<div><img src="../assets/33.png" class="pic"></div>
						<div>军事频道</div>
					</div>
				</div>
				<div class="line">
					<div class="tou">
						<div><img src="../assets/34.png" class="pic"></div>
						<div>国内新闻</div>
					</div>
					<div class="tou">
						<div><img src="../assets/35.png" class="pic"></div>
						<div>国际新闻</div>
					</div>
					<div class="tou">
						<div><img src="../assets/36.png" class="pic"></div>
						<div>社会新闻</div>
					</div>
				</div>
				<div class="line">
					<div class="tou">
						<div><img src="../assets/37.png" class="pic"></div>
						<div>数码测评</div>
					</div>
					<div class="tou">
						<div><img src="../assets/38.png" class="pic"></div>
						<div>旅游频道</div>
					</div>
					<div class="tou">
						<div><img src="../assets/39.png" class="pic"></div>
						<div>电影资讯</div>
					</div>
				</div>
				<div class="line">
					<div class="tou">
						<div><img src="../assets/40.png" class="pic"></div>
						<div>涨姿势</div>
					</div>
					<div class="tou">
						<div><img src="../assets/41.png" class="pic"></div>
						<div>百思不得姐</div>
					</div>
					<div class="tou">

					</div>
				</div>
				<div style="height: 5rem;"></div>
			</van-tab>
			<van-tab title="精读">
				<div class="hh">
					<div class="ma">
						<div class="pic1">
							<div><img src="../assets/42.png" class="lun3"></div>
							<div class="join2">“进一波死一波”，共享厨房不香了？</div>
							<div class="qiu2">餐饮老板内参 08月04日</div>
						</div>
						<div class="pic2">
							<div><img src="../assets/43.png" class="lun3"></div>
							<div class="join2">海底捞张勇“捞”金离场？</div>
							<div class="qiu2">中新经纬 08月03日</div>
						</div>
						<div class="pic2">
							<div><img src="../assets/44.png" class="lun3"></div>
							<div class="join2">悬崖上的华谊兄弟</div>
							<div class="qiu2">盒饭财经 08月04日</div>
						</div>
						<div class="pic2">
							<div><img src="../assets/45.png" class="lun3"></div>
							<div class="join2">地方政府放卫星</div>
							<div class="qiu2">非凡油条 08月04日</div>
						</div>
						<div class="pic2">
							<div><img src="../assets/46.png" class="lun3"></div>
							<div class="join2">这些美企不听特朗普的话力挺中国</div>
							<div class="qiu2">一见财经 08月05日</div>
						</div>
						<div class="pic2">
							<div><img src="../assets/47.png" class="lun3"></div>
							<div class="join2">抢滩动力电池</div>
							<div class="qiu2">子弹财经 08月05日</div>
						</div>
						<div style="height: 7rem;"></div>
					</div>
				</div>
			</van-tab>
			<van-tab></van-tab>
		</van-tabs>
		<div class="search">
			<van-icon name="search" />
		</div>
	</div>
</template>

<script>
	// @ is an alias to /src
	// import HelloWorld from '@/components/HelloWorld.vue'

	export default {
		data() {
			return {
				active: '',
				current: 0,
			}
		},
		methods: {
			onChange(index) {
				this.current = index;
			},
		},

	}
</script>
<style scoped>
	.search {
		position: absolute;
		top: 1.2rem;
		right: 3.7rem;
		font-size: 1.7rem
	}

	.ma {
		margin-left: 2.2rem;
	}

	.life {
		margin-top: 1.5rem;
		font-size: 1.6rem;
		font-weight: bold;
		color: #999;
	}

	.life2 {
		margin-top: 1rem;
		font-size: 1.6rem;
		font-weight: bold;
		color: #999;
	}

	.yang {
		color: #999;
	}

	.flex {
		display: flex;
		margin-top: 0.3125rem;
	}

	.zhi {
		border: 0.0625rem solid red;
		width: 2.7rem;
		text-align: center;
		border-radius: 0.2rem;
		color: red;
		margin-left: 1rem;
	}

	.join {
		margin-top: 1rem;
		font-size: 1.5rem;
		font-weight: bold;
	}
	.qiu {
		color: #999;
	}
    .join2 {
		margin-top: 1rem;
		font-size: 1.5rem;
		font-weight: bold;
		margin-left: 1.25rem;
	}
	.qiu2{
		color: #999;
		margin-left: 1.25rem;
		margin-top: 0.625rem;
	}
	.gray {
		width: 100%;
		height: 0.6rem;
		margin-top: 0.9375rem;
		background: #eaeaea;
	}

	.day {
		width: 30%;
		margin-top: 1.25rem;
	}

	.custom-indicator {
		position: absolute;
		right: 0.3125rem;
		bottom: 0.3125rem;
		padding: 0.125rem 0.3125rem;
		font-size: 0.75rem;
		background: rgba(0, 0, 0, 0.1);
	}

	.lun {
		width: 94%;
	}

	.lun2 {
		width: 100%;
		margin-top: 1rem;
	}

	.lun3 {
		width: 100%;
	}

	.top {
		margin-top: 1rem;
	}

	.line {
		display: flex;
		width: 100%;
		margin-top: 2rem;
	}

	.line>div {
		flex: 1;
	}

	.pic {
		width: 100%
	}

	.tou {
		text-align: center;
	}

	.tou>div:nth-child(2) {
		margin-top: 0.5rem;
	}

	.hh {
		background: #fbfbfb;
		height: 62.5rem;
		padding-top: 2rem;
	}

	.pic1 {
		height: 27rem;
		background: #fff;
		width: 94%;
		border-radius: 0.625rem;
	}
	.pic2 {
		height: 27rem;
		background: #fff;
		width: 94%;
		border-radius: 0.625rem;
		margin-top: 2rem;
	}
</style>
