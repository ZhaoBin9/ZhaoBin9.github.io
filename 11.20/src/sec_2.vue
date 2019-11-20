<template>
      <div id="sec_2">
            <div id="sec2">
            <sec_2_1 v-for="item in arr" :aitem="item"></sec_2_1>
            </div>
            <div id="sec2">
                  <sec_2_1 v-for="item in arr1" :aitem="item"></sec_2_1>
            </div>
      </div>
</template>

<script>
      import Sec_2_1 from './sec_2_1.vue'
      export default {
            data(){
                  return {
                        arr:[
                              {
                                    imgurl: '',
                                    title: '跨屏展示',
                                    text: '一个炫酷的网站才配得上创业者的新潮创意.起飞页采用HTML5最新技术,拥有大气舒适的界面和众多精美模板'
                              },
                              {
                                    imgurl: '',
                                    title: '页面酷炫',
                                    text: '一个炫酷的网站才配得上创业者的新潮创意.起飞页采用HTML5最新技术,拥有大气舒适的界面和众多精美模板'
                              },
                              {
                                    imgurl: '',
                                    title: '简单易用',
                                    text: '一个炫酷的网站才配得上创业者的新潮创意.起飞页采用HTML5最新技术,拥有大气舒适的界面和众多精美模板'
                              },
                              {
                                    imgurl: '',
                                    title: '完全免费',
                                    text: '一个炫酷的网站才配得上创业者的新潮创意.起飞页采用HTML5最新技术,拥有大气舒适的界面和众多精美模板'
                              },
                        ],
                        arr1: [
                              {
                                    imgurl: '',
                                    title: '跨屏展示',
                                    text: '一个炫酷的网站才配得上创业者的新潮创意.起飞页采用HTML5最新技术,拥有大气舒适的界面和众多精美模板'
                              },
                              {
                                    imgurl: '',
                                    title: '页面酷炫',
                                    text: '一个炫酷的网站才配得上创业者的新潮创意.起飞页采用HTML5最新技术,拥有大气舒适的界面和众多精美模板'
                              },
                              {
                                    imgurl: '',
                                    title: '简单易用',
                                    text: '一个炫酷的网站才配得上创业者的新潮创意.起飞页采用HTML5最新技术,拥有大气舒适的界面和众多精美模板'
                              },
                              {
                                    imgurl: '',
                                    title: '完全免费',
                                    text: '一个炫酷的网站才配得上创业者的新潮创意.起飞页采用HTML5最新技术,拥有大气舒适的界面和众多精美模板'
                              }
                        ]
                  }
            },
            components: {
                  Sec_2_1
            }
      }
</script>

<style scoped>
      #sec_2 {
            padding: 8% 0;
            background-image: url('https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvMGIwYWIwZWU0YWRjNDQ5Yjg2YzFhZjMyOWNkZDc1MDYuanBn.jpg'); background-repeat:no-repeat; background-size:cover; background-attachment:fixed; background-position:0 0%;
      }

      #sec2 {
            display: flex;
            justify-content: space-around;
            flex-wrap: nowrap;
            margin: 10px 0;
      }
</style>