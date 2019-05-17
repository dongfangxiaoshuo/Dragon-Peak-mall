<template>
  <div class="headlines">

    <div class="longhot_wrap">
      <img class="longhot" src="../../public/img/index/longdhot.png" alt="">
    </div>

    <div class="banner_title">
      <van-tag type="danger">推荐</van-tag><span>养龙，心态比龙还重要</span>
    </div>

    <div class="headlines_title">
      更多
    </div>
  
   
  </div>
</template>

<script>
export default {
  name: 'Headlines',
  data () {
    return {
     
    }
  },

  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .headlines{
    margin: 0px 10px;
    height: 30px;
    width:22rem;
    display: flex;
    justify-content:space-around;
    border-radius:.3rem;
    background: #efefef;
  }
  .longhot{
    padding: 8px 0;
    height:50%;
  }
  .banner_title span{
    margin-left:5px; 
    
  }

  .banner_title{
    background: #f5f5f5;
    padding: 3px 7px;

  }
  .headlines_title{
    line-height: 30px;
    color:#666;
    font-size: 14px;
    

    /* line-height: 2.5rem; */
 

  }

 
</style>
