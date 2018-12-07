<style>
@import '../starry_view/style.css';
</style>

<template>
  <div class="com-cention">
    <Header/>
    <section class="com-publicity">
        <div id="particles-js" class="isd"></div>

        <div class="backyuan">
            <div class='backimg'></div>
        </div>
        <div class="logoback"></div>
        <div class="cneteron">
            <canvas id="canvas" class="canvas">
                当前浏览器不支持Canvas，请更换浏览器后再试
            </canvas>
            <div class="cendiv hu1"></div>
            <div class="cendiv hu2"></div>
            <div class="cendiv hu3"></div>
            <div class="cendiv hu4"></div>
            <div class="cendiv hu5"></div>
            <div class="cendiv hu6"></div>
            <div class="cendiv hu7"></div>
            <div class="cendiv hu8"></div>
            <div class="cendiv hu9"></div>
        </div>
        <img src="../assets/loging.png" class="imgshyen" alt="">
<<<<<<< HEAD
        <div class="aosucenter">
             <h3 class="h3">中琛云链积分通兑（ZC-IN）</h3>
             <div class="txt">是基于Hyperledger Fabric 1.x基础之上自主研发包区块链底层、SDK、浏览器、运维平台的商用级区块链级产品</div>
             <el-button class="btn" type="primary">立即体验</el-button>
        </div>
    </section>
    <section class="">
        
    </section>
=======
    </section>
    
>>>>>>> 05c8a4be60b4e0406c06aee4b005357dba6765ab
  </div>
</template>

<script>

import Header from './common/header.vue'
import '../starry_view/particles.min.js'
import '../starry_view/app.js'
export default {
  data () {
    return {
        
    }
  },
  components:{
    Header
  },
  created(){
    this.cheng();
  },
  methods:{
      cheng(){
        window.onload=function(){
            var canvas=document.getElementById('canvas');
            canvas.width=660;
            canvas.height=660;
            var context=canvas.getContext('2d');
           
            //context.arc(x,y,r,sAngle(开始),eAngle（结束）,counterclockwise);
            context.beginPath();
            context.arc(330,330,280,0.8*Math.PI,1.62*Math.PI, false);
            context.lineWidth=2;
            context.strokeStyle="#00a2e9";
            context.stroke();
            context.closePath();

            context.beginPath();
            context.arc(330,330,198,0.68*Math.PI,1.2*Math.PI, false);
            context.lineWidth=2;
            context.strokeStyle="#00a2e9";
            context.stroke();
            context.closePath();

            context.beginPath();
            context.arc(330,330,280,0*Math.PI,0.35*Math.PI, false);
            context.lineWidth=2;
            context.strokeStyle="#00a2e9";
            context.stroke();
            context.closePath();
            
            context.beginPath();
            context.arc(330,330,280,0*Math.PI,0.35*Math.PI, false);
            context.lineWidth=2;
            context.strokeStyle="#00a2e9";
            context.stroke();
            context.closePath();
            
            context.beginPath();
            context.arc(330,330,200,1.85*Math.PI,0.25*Math.PI, false);
            context.lineWidth=2;
            context.strokeStyle="#00a2e9";
            context.stroke();
            context.closePath();

            context.beginPath();
            context.arc(330,330,180,1.88*Math.PI,0.23*Math.PI, false);
            context.lineWidth=2;
            context.strokeStyle="#00a2e9";
            context.stroke();
            context.closePath();

            context.beginPath();
            context.arc(330,330,280,0.45*Math.PI,0.7*Math.PI, false);
            context.lineWidth=2;
            context.strokeStyle="#00a2e9";
            context.stroke();
            context.closePath();

            context.beginPath();
             context.setLineDash([7]);//虚线
            context.arc(330,330,230,1.15*Math.PI,1.7*Math.PI, false);
            context.lineWidth=2;
            context.strokeStyle="#00a2e9";
            context.stroke();
            context.closePath();

        }
      }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less">
  @import '../style/common.less';
  @import '../style/index.less';
 
</style>
<style socpod>
    
    
</style>

