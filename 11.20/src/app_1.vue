<template>
      <div id="app_1" style="width:22%">
            <div><img :src="item.imgurl" alt=""></div>
            <p class="a-title">{{item.title}}</p>
            <p class="a-text">{{item.text}}</p>
      </div>
</template>

<script>
      export default {
            props: ['aitem'],
            data(){
                  return {
                        item: this.aitem
                  }
            }
      }
</script>

<style scoped>

      #app_1>div{
            height: 100px;
            text-align: center;
      }

      #app_1>div img {
            height: 100%;
      }

      #app_1 .a-title {
            font-size: 16px;
            line-height: 30px;
            color: #696969;
            margin-bottom: 8px;
      }

      #app_1 .a-text {
            font-size: 14px;
            color: #808080;
            line-height: 22px;
      }
</style>