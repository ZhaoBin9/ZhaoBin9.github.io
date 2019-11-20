<template>
	<div id="container">
		<div class="c-title">
			<h3>您的创业梦想需要一个非同凡响的网站</h3>
			<p>云建站倾力打造的一个从网站建设.网网站运营管理到网站推广的自动化免费建站平台</p>
		</div>
		<div class="c-content">
			<div>
				<app_1 v-for="item in arr" :aitem="item">{{item}}</app_1>
			</div>
		</div>
	</div>
</template>

<script>
	import App_1 from './app_1.vue'
	export default {
		data(){
		  return {
		  	arr: [
                              {
                                    imgurl: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvZjgxMjkwZTg3YTEzM2ZkNWFiM2IzY2ExNjdhNTA3ZDgucG5n.png',
                                    title: '页面要炫酷,颜值要高',
                                    text: '人靠衣装马靠鞍,一个炫酷的网站才配得上创业者的新潮创 意.微企点采用HTML5最新技术,拥有大气舒适的界面和众多 精美模板,用起飞页制作一个高逼格.高颜值的炫酷网站, 让您的创业项目脱颖而出,非同凡响.'
                              },
                              {
                                    imgurl: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvY2JmYjViODAyM2M4ZjczMzU4YmY0OGIxMmEwNmRjNDkucG5n.png',
                                    title: '简单易用,随需而变',
                                    text: '互联网创业瞬息万变,天下武功,唯快不破.创业者可以按需选择起飞页中精美的网页模板,预置栏目,快速添加和编辑网页无需编程,一步即创建一个炫酷高颜值的网站.网站从无到有,倚马可待.'
                              },
                              {
                                    imgurl: 'https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvMzY3N2Y5N2FhMjQ5YThmNmFlODUxNGJiM2E1NWExZGEucG5n.png',
                                    title: '支持多终端跨屏展示',
                                    text: '在移动互联网全面渗透时,创业者需要一个随屏幕大小不同而自动伸缩的网站,这样同一份内容都可为不同终端用户带来最佳用户体验.微企点使用最新的HTML5响应式技术,网页界面随不同屏幕尺寸自动伸缩.'
                              }
                        ]
		  }
		},
		methods: {
			btn() {
				alert('hello')
			}
		},
		components: {
			App_1
		}
	}
</script>

<style>
	* {
		margin: 0;
		padding: 0;
	}

	#container {
		text-align: center;
		padding-bottom: 70px;
      }

	#container .c-title {
		margin: 8% 0 5%;
	}

      #container .c-title h3 {
		color: rgb(232, 76, 61);
            font-size: 30px;
            font-weight: normal;
            font-style: normal;
		line-height: 48px;
		padding-bottom: 20px;
      }

	#container .c-title p {
		color: rgb(105, 105, 105);
		line-height: 1.5em;
		font-size: 18px;
	}

      #container .c-content>div {
		display: flex;
		justify-content: space-around;
		flex-wrap: nowrap;
	}

</style>