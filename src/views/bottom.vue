<template>
	<div class="bottom">
		<div class="ma">
			<div class="find">发现</div>
			<div class="top">
				<van-swipe :loop="false" :width="300">
					<van-swipe-item><img src="../assets/56.png" class="lun" /></van-swipe-item>
					<van-swipe-item><img src="../assets/57.png" class="lun" /></van-swipe-item>
					<van-swipe-item><img src="../assets/58.png" class="lun" /></van-swipe-item>
					<van-swipe-item><img src="../assets/59.png" class="lun" /></van-swipe-item>
				</van-swipe>
			</div>
		</div>
		<van-tabs>
			<van-tab v-for="index in 8" :title="'标签 ' + index" :key="index">
				内容 {{ index }}
			</van-tab>
		</van-tabs>
	</div>
</template>

<script>

</script>

<style scoped>
	.ma {
		margin-left: 2.2rem;
	}

	.find {
		margin-top: 1rem;
		font-size: 1.4rem;
	}

	.lun {
		width: 94%;
	}

	.top {
		margin-top: 1.5rem;
	}
</style>
