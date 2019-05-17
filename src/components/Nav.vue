<template>
  <div class="nav">
    <ul>

      <li>
        <img src="../../public/img/index/1509677183918045281.png" alt="">
        <span>龙鱼</span>
      </li>

       <li>
        <img src="../../public/img/index/1509677144682228134.png" alt="">
        <span>魟鱼</span>
      </li>

       <li>
        <img src="../../public/img/index/1509677072309036244.png" alt="">
        <span>虎鱼</span>
      </li>

       <li>
        <img src="../../public/img/index/1509677036438611025.png" alt="">
        <span>罗汉鱼</span>
      </li>

       <li>
        <img src="../../public/img/index/1509677003419716558.png" alt="">
        <span>锦鲤鱼</span>
      </li>

      <li>
        <img src="../../public/img/index/1509676883385926151.png" alt="">
        <span>鱼缸</span>
      </li>

       <li>
        <img src="../../public/img/index/1509676855173622770.png" alt="">
        <span>器材配件</span>
      </li>

       <li>
        <img src="../../public/img/index/1509676615033110228.png" alt="">
        <span>滤材</span>
      </li>

       <li>
        <img src="../../public/img/index/1509677779190022774.png" alt="">
        <span>鱼文化</span>
      </li>

       <li>
        <img src="../../public/img/index/1509676041489774944.png" alt="">
        <span>全部商品</span>
      </li>


    </ul>
  </div>
</template>

<script>
export default {
  name: 'Nav',
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
  .nav{
    padding: 10px 0;
    width: 100%;
  } 
  .nav ul{
    display: flex;
    flex-wrap:wrap;
    justify-content:space-around;
  }
  .nav li{
    height: 3rem;
    width: 3rem;
    padding: 0px 10px 30px 10px;
    line-height: 20px;
    font-size: 12px;
    /* display: flex;
    flex-direction:column; */
    
  }
  .nav li img{
    height: 100%;
    width: 100%
  }
 
</style>
