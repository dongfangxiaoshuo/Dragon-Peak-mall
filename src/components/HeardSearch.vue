<template>
  <div class="search">
    <img  class="shop_logo" src="../../public/img/index/shop_logo.png" alt="">
    <van-search placeholder="请输入搜索关键词" v-model="value" background="#E71F19"  shape="round"/>
    <img  class="redbag" src="../../public/img/index/redbag.png" alt="">
  </div>
</template>

<script>
export default {
  name: 'Search',
  data () {
    return {
      value: ''
    }
  },

  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .search{
    display: flex;
    height: 3.5rem;
    width: 100%;
    background-color: #E71F19;
    justify-content:space-around;
  }
  .search .shop_logo{
    margin: .8rem;
    height: 1.5rem;
    width: 4rem;
  }
  .search .redbag{
    margin: .4rem;
    height: 3rem;
    width:2.613rem;
  }
 
</style>
