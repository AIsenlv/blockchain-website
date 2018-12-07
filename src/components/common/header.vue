<template>
    <header class="header">
    <div class="nav">
        <el-row >
          <el-col :span="4" class="logo"><img src="../../assets/LOGO.png" alt=""/></el-col>
          <el-col :span="12" >
              <el-menu :default-active="activeIndex" class="el-menu-demo listIndex" mode="horizontal" @select="handleSelect">
                <el-menu-item index="1">首页</el-menu-item>
<<<<<<< HEAD
                <el-submenu index="2">
                <template slot="title">我的工作台</template>
                <el-menu-item index="2-1" style="width:100%;height:110px;">
                  <div style="width:100%;height:110px;">
                      <div class="hovecen">
                          <div class="list">
                              <div class="inblock middle icon"><img  src="../../assets/png1.svg" alt=""></div>
                              <div class="inblock middle ont">
                                 <div class="txt">积分商城</div>
                                 <div class="thic">区块链构建多商品共享信息，让积分流动推广商品</div>
                              </div>
                          </div>
                          <div class="list">
                              <div class="inblock middle icon"><img  src="../../assets/png3.svg" alt=""></div>
                              <div class="inblock middle ont">
                                 <div class="txt">商品防伪追溯</div>
                                 <div class="thic">区块链构独一无二商品信息。</div>
                              </div>
                          </div>
                          <div class="list">
                              <div class="inblock middle icon"><img  src="../../assets/png2.svg" alt=""></div>
                              <div class="inblock middle ont">
                                 <div class="txt">供应链</div>
                                 <div class="thic">区块链构建物流区块链</div>
                              </div>
                          </div>
                          <div class="list">
                              <div class="inblock middle icon"><img  src="../../assets/png4.svg" alt=""></div>
                              <div class="inblock middle ont">
                                 <div class="txt">敬请期待</div>
                                 <div class="thic">区块链构更多的应用场景</div>
                              </div>
                          </div>
                      </div>
                  </div>
                </el-menu-item>
                
              </el-submenu>
=======
                <el-menu-item index="2">产品方案</el-menu-item>
>>>>>>> 05c8a4be60b4e0406c06aee4b005357dba6765ab
                <el-menu-item index="3">技术文档</el-menu-item>
                <el-menu-item index="4">关于我们</el-menu-item>
              </el-menu>  
          </el-col>
          <el-col :span="8" class="textright hodetop">
            <a href="#" class="topa">控制台</a>
            <el-button type="primary">登录/注册</el-button>
          </el-col>
        </el-row>
        </div>
  </header>
</template>
<script>
export default {
  data () {
    return {
      activeIndex:'1',
      
    }
   
  },
   methods:{
       handleSelect(key, keyPath) {
        console.log(key, keyPath);
      }
    }
}
</script>
<style lang="less" socpod>
    .el-menu--horizontal{
        width: 100%;
        left: 0!important;
        .el-menu--popup-bottom-start{
          margin-top: 0px;
        }
        .el-menu--popup{
            border-radius: 0;
            background: #1b1d31!important;
            opacity: 0.9;
            color: #fff;
        }
        .el-menu .el-menu-item{
            background: #1b1d31!important;
            opacity: 0.9;
            color: #fff;
            &:hover{
                color: #fff;
            }
        }
        .hovecen{
          width: 1200px;
          margin:0 auto;
          .list{
            padding-top: 20px;
            display: inline-block;
            .icon{
              width: 38px;
               margin-right: 20px;
              img{width:100%;}
            }
            .ont{
              margin-right: 45px;
              width:180px;
              .txt{
                font-size: 18px;
                color: #fdfefe;
              }
              .thic{
                font-size: 14px;
                color: #909090;
                white-space: initial;
                line-height: 20px;
              }
            }


          }
        }
    }
</style>
