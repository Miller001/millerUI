<template>
	<div id="app">
		<img alt="Vue logo" src="./assets/logo.png" />
		<Demo />
		<m-card imgSrc="uniapp.png" summary="2021最新版 uni-app从入门到进阶 系统完成项目实战" />
		<br />
		<m-card imgSrc="xingneng.png" summary="前端性能优化企业级解决方案 6大角度+大厂视野">
			<template v-slot:footer>
				<div class="footer">
					<div class="level">中级 · 918人报名</div>
					<div class="price">￥299.00</div>
				</div>
			</template>
		</m-card>
		<br />
		<m-card imgSrc="vue.png" :width="370" :imgHeight="90">
			路线专为想学Vue却无从下手的人群设计，以实际项目为例，逐层深入，学透Vue。
			<template v-slot:footer>
				<div class="footer-vue">
					<div class="level">4步骤 · 5门课</div>
					<div class="level">19868收藏</div>
				</div>
			</template>
		</m-card>
	</div>
</template>

<script>
export default {
	name: 'App',
	components: {},
};
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
.footer {
	padding: 0 8px;
	font-size: 12px;
	text-align: left;
}
.level {
	color: #9199a1;
	margin-bottom: 8px;
}
.price {
	color: #f01414;
}
.footer-vue {
	display: flex;
	justify-content: space-between;
	padding: 0 8px;
	font-size: 12px;
}
</style>
