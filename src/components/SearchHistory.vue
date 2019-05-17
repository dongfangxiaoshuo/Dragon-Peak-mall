<template>
  <div class="searchhistory">
    <van-cell-group>
    <van-cell title="搜索记录"/>
    <van-cell value="金龙鱼" />
    <van-cell value="鲳鱼" />
    <van-cell value="黄花鱼" />
    <van-cell title="热门搜索"/>
    <div class="tag">
      <van-tag plain>大黄花</van-tag>
      <van-tag plain>黄龙玉</van-tag>
      <van-tag plain>石头蟹</van-tag>
      <van-tag plain>八爪鱼</van-tag>
      <van-tag plain>鲸鱼</van-tag>
      <van-tag plain>平昌鱼</van-tag>
    </div>
    
  </van-cell-group>

      
    
  </div>
</template>

<script>
export default {
  name: 'SearchHistory',
  data () {
    return {
     
    }
  },

  props: {
    
  },
  methods:{
    
   
  } 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .tag{
    display: flex;
    justify-content:space-around;
  }
 
</style>
