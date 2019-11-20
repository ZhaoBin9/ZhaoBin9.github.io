<template>
      <div id="sec2_1" style="width:20%;">
            <div class="s-img">
                  
            </div>
            <h3>{{item.title}}</h3>
            <p>{{item.text}}</p>
      </div>
</template>

<script>
export default {
      props: ['aitem', 'aitem1'],
      data(){
            return {
                  item: this.aitem,
            }
      }
}
</script>

<style scoped>
      #sec2_1 {
            text-align: center;
      }

      #sec2_1 .s-img {
            width: 50px;
            height: 50px;
            margin: 0 auto;
            padding: 10px;
            background-color: #fff;
            border-radius: 3px;
      }

      #sec2_1  h3 {
            font-size: 16px;
            letter-spacing: 1px;
            color: #D3D3D3;
      }

      #sec2_1  p {
            line-height: 1.3em;
            letter-spacing: 1px;
            color: #A9A9A9;
      }
</style>