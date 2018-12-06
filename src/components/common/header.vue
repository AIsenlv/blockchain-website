<template>
    <header class="header">
    <div class="nav">
        <el-row >
          <el-col :span="4" class="logo"><img src="../../assets/LOGO.png" alt=""/></el-col>
          <el-col :span="12" >
              <el-menu :default-active="activeIndex" class="el-menu-demo listIndex" mode="horizontal" @select="handleSelect">
                <el-menu-item index="1">首页</el-menu-item>
                <el-menu-item index="2">产品方案</el-menu-item>
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