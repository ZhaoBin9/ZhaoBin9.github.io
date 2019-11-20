<template>
      <div id="section">
            <div class="s-title">
                  <p>云建站自助平台</p>
                  <span>上手快.颜值高.跨多屏.自传播.全免费.</span>
            </div>
            <dv class="s-content">
                  <p>在 起飞页自助建站平台，您不需要任何编程基础，就能做出功能强大，效果出众的专业级网站，您所要做的仅是选择网站模板、输入图片文字，以及鼠标拖拉拽；真正 的响应式建站，无论是在电脑的大屏幕，还是手机小屏幕上，网站都能友好地展示；您的访客还可以注册成为会员，并进行在线购物；当然，如果您需要多语言版 本，起飞页也可以轻松为您实现。</p>
            </dv>
      </div>
</template>

<script>
import { setInterval } from 'timers';
      export default {
            data(){
                  return {
                        arr:[
                              '每一个模版都经过设计、制作、测试、改进等多道工序，力求在达到赏心悦目的艺术视觉效果的同时，又容易定制改变。除此以外，多达180个精美的常用设计模式和30余个功能组件让您在自助建站时得心应手，事半功倍。',
                              '在 起飞页自助建站平台，您不需要任何编程基础，就能做出功能强大，效果出众的专业级网站，您所要做的仅是选择网站模板、输入图片文字，以及鼠标拖拉拽；真正 的响应式建站，无论是在电脑的大屏幕，还是手机小屏幕上，网站都能友好地展示；您的访客还可以注册成为会员，并进行在线购物；当然，如果您需要多语言版 本，起飞页也可以轻松为您实现。'
                        ]
                  }
            },
            mounted(){
                  const op = section.querySelector('.s-content p');
                  let num = 1;
                  setInterval( () => {
                        num>=1 ? num = 0 : num++;
                        op.innerHTML = this.arr[num];
                  }, 10000)
            }
      }
</script>

<style scoped>
      #section {
            background-image: url('https://ccdn.goodq.top/caches/38ad257d4bd31c1e897c7f2f4f0c83f3/aHR0cHM6Ly81NmM0MmI1MDY3NmYxLnQ3My5xaWZlaXllLmNvbS9xZnktY29udGVudC91cGxvYWRzLzIwMTYvMDIvMWYyYjI0N2JjYTc5MjhkYzIyOTRiMjc0M2UyZDI1MWQuanBn.jpg');
            background-repeat:no-repeat;
            background-size:cover;
            background-attachment:fixed;
            background-position:0 0%;
            text-align: center;
      }

      #section .s-title {
            font-size: 24px;
            height: 130px;
            line-height: 35px;
            background-color: rgba(5,5,5,0.3);
      }

      #section .s-title p {
            color: #fff;
            padding-top: 25px;
      }

      #section .s-title span {
            color: rgb(232, 76, 61);
      }

      #section .s-content {
            line-height: 1.8;
            color: #fff;
      }

      #section .s-content p {
            letter-spacing: 3px;
            padding: 10% 11%;
      }
</style>