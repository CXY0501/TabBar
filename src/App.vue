<template>
  <div id="app">
   <tabbar>
     <tabbaritem>
       <img slot="itemicon" src="./assets/img/tabbar/首页 (1).png" alt="">
       <img slot="itemicon_active" src="./assets/img/tabbar/首页.png" alt="">
       <div slot="itemname">首页</div>
     </tabbaritem>
     <tabbaritem>
       <img slot="itemicon" src="./assets/img/tabbar/类目 品类 分类 类别 (1).png" alt="">
       <img slot="itemicon_active" src="./assets/img/tabbar/类目 品类 分类 类别.png" alt="">
       <div slot="itemname">品类</div>
     </tabbaritem>
     <tabbaritem>
       <img slot="itemicon" src="./assets/img/tabbar/购物车空 (1).png" alt="">
       <img slot="itemicon_active" src="./assets/img/tabbar/购物车空.png" alt="">
       <div slot="itemname">购物车</div>
     </tabbaritem>
     <tabbaritem>
       <img slot="itemicon" src="./assets/img/tabbar/我的 (1).png" alt="">
       <img slot="itemicon_active" src="./assets/img/tabbar/我的.png" alt="">
       <div slot="itemname">我的</div>
     </tabbaritem>
   </tabbar>
  </div>
</template>



<script>
import tabbar from './components/tabbar/tabbar'
import tabbaritem from './components/tabbar/tabbaritem'

export default {
  name: 'App',
  components: {
   tabbar,
   tabbaritem
  }
}
</script>
  
<style>
 @import "./assets/css/base.css";
</style>
