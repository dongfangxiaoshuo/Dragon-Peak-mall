<template>
  <div class="footnav">
    <van-tabbar v-model="active" >
      <van-tabbar-item icon="home-o">首页</van-tabbar-item>
      <van-tabbar-item icon="search" to="/search" >搜索</van-tabbar-item>
      <van-tabbar-item icon="shopping-cart-o" to="#" info="5">购物车</van-tabbar-item>
      <van-tabbar-item icon="contact" to="/me" info="20">我的</van-tabbar-item>
    </van-tabbar>

    <!-- <van-tabbar
  v-model="active"
  active-color="#07c160"
>
  <van-tabbar-item icon="home-o">标签</van-tabbar-item>
  <van-tabbar-item icon="search">标签</van-tabbar-item>
  <van-tabbar-item icon="freinds-o">标签</van-tabbar-item>
  <van-tabbar-item icon="setting-o">标签</van-tabbar-item>
</van-tabbar> -->


    
  </div>
</template>

<script>
export default {
  name: 'FootNav',
  data() {
    return {
      active:1
    }
  },

  props: {
    
  },
  methods:{
    //跳转页面
   
  } 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .footnav{
    margin-top:2rem; 
  }
 
</style>
