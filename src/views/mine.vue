<template>
	<div >
		<div class="mine"> 
			<div class="my">我的</div>
			<div class="mydic">
				<div><img width="50rem" src="../assets/2.png" /></div>
				<div><img width="43rem" src="../assets/3.png" /></div>
				<div><img width="45rem" src="../assets/4.png" /></div>
				<div>
					<router-link to="deng"><img width="34rem" src="../assets/5.png" /></router-link>
				</div>
			</div>
			<div class="cen">
				<div><img class="info" src="../assets/6.png"> </div>
				<div class="text"><router-link to="deng">消息中心</router-link></div>
			</div>
			<div class="cen2">
				<div><img class="info" src="../assets/7.png"> </div>
				<div class="text2"><router-link to="deng">收藏与历史</router-link></div>
			</div>
		</div>
		<div class="gray"></div>
		<div class="mine">
			<div class="cen2">
				<div><img class="info" src="../assets/8.png"> </div>
				<div class="text2">我的资产</div>
			</div>
			<div class="cen2">
				<div><img class="info" src="../assets/9.png"> </div>
				<div class="text2">福利商城</div>
			</div>
			<div class="cen2">
				<div><img class="info" src="../assets/10.png"> </div>
				<div class="text2">活动中心</div>
			</div>
			<div class="cen2">
				<div><img class="info" src="../assets/11.png"> </div>
				<div class="text2">主题皮肤</div>
			</div>
		</div>
		<div class="gray"></div>
		<div class="mine">
			<div class="cen2">
				<div><img class="info" src="../assets/12.png"> </div>
				<div class="text2">推送资讯</div>
			</div>
			<div class="cen2">
				<div><img class="info" src="../assets/13.png"> </div>
				<div class="text2">设置</div>
			</div>
			<div class="cen2">
				<div><img class="info" src="../assets/14.png"> </div>
				<div class="text2">意见反馈</div>
			</div>
		</div>
		<div class="gray"></div>
	</div>

</template>

<script>
</script>

<style scoped>
	.my{
		margin-top: 1.5rem;
	}
	.mine {
		font-size: 1.4rem;
		margin-left: 2rem;
	
	}

	.mydic {
		display: flex;
		margin-top: 3rem;
		box-sizing: border-box;
	}

	.mydic>div {
		flex: 1;
		text-align: center;
	}
    .info{
		width: 2rem;
	}
	.cen{
		color: #666666;
		margin-top: 5rem;
		display: flex;
	}

	.text{
		margin-left: 1rem;
		font-size:0.625rem ;
	}
	.cen2{
		color: #666666;
		margin-top: 2rem;
		display: flex;
	}
	.text2{
		margin-left: 1rem;
		font-size:0.625rem ;
		margin-top: 0.3125rem;
	}
	.gray{
		width: 100%;
		height:0.6rem;
		margin-top: 0.9375rem;
		background: #eaeaea;
	}
</style>
