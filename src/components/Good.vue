<template>
  <div class="good">
    <van-cell title="器材" icon="fire"  is-link />
    <div>
      <ul class="good_list">

        <li>
          <img src="../../public/img/index/10678534_thumb_G_1532487030762.jpg" alt="">
          <span class="good_info">智鱼节能电子加热棒 鱼缸加热棒自</span>
          <div class="good_price">
            <div>
              <p>140.00</p>
              <del>168.00</del>
            </div>
            <div>
              <van-icon name="cart-o" color="white" class="cart"/>  
            </div>
          </div>
        </li>

        <li>
          <img src="../../public/img/index/133_95582e46378e0c4a70ff7a7ef5313a6c_240.jpg" alt="">
          <span class="good_info">新品滤材金龙红龙鱼与魟鱼</span>
          <div class="good_price">
            <div>
              <p>22.00</p>
              <del>26.00</del>
            </div>
            <div>
              <van-icon name="cart-o" color="white" class="cart" />  
            </div>
          </div>
        </li>

        <li>
          <img src="../../public/img/index/10677916_thumb_G_1530753757693.jpg" alt="">
          <span class="good_info">君致龙缸 LC款 暗夜黑</span>
          <div class="good_price">
            <div>
              <p>7800.00</p>
              <del>7800.00</del>
            </div>
            <div>
              <van-icon name="cart-o" color="white" class="cart" />  
            </div>
          </div>
        </li>

        <li>
          <img src="../../public/img/index/10677190_thumb_G_1528957076691.jpg" alt="">
          <span class="good_info">玛豆水族用品鱼缸过滤棉过滤材料</span>
          <div class="good_price">
            <div>
              <p>48.00</p>
              <del>57.59</del>
            </div>
            <div>
              <van-icon name="cart-o" color="white" class="cart"/>  
            </div>
          </div>
        </li>

        <li>
          <img src="../../public/img/index/10643086_thumb_G_1496814070747.jpg" alt="">
          <span class="good_info">【格池小绵羊】 透明毡 日本藤</span>
          <div class="good_price">
            <div>
              <p>42.00</p>
              <del>50.40</del>
            </div>
            <div>
              <van-icon name="cart-o" color="white" class="cart" />  
            </div>
          </div>
        </li>

        <li>
          <img src="../../public/img/index/10674325_thumb_G_1522293805646.jpg" alt="">
          <span class="good_info">玛风过滤培菌网杭州玛豆环保科技有</span>
          <div class="good_price">
            <div>
              <p>57.00</p>
              <del>57.00</del>
            </div>
            <div>
              <van-icon name="cart-o" color="white" class="cart" />  
            </div>
          </div>
        </li>

       
        
      </ul>
    </div>
   

  
    
   
  </div>
</template>

<script>
export default {
  name: 'Good',
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

  .van-icon-fire:before{
    color:red;
  }
  .van-cell__title, .van-cell__value{
    margin-left: -17rem;
    font-weight: 600;
    line-height: 1.6rem;
  }
  .good_list{
    display: flex;
    justify-content:space-around;
    flex-wrap:wrap;
    padding: 10px 4px;
    overflow: hidden;
  }

  .good_list li{
    padding: 10px;
    height: 13rem;
    width: 6rem;
    font-size: 12px;
  }
  .good_info{
    line-height: 20px;
  }

  .good_list li img{
    height: 7.1rem;
    width: 6.5rem
  }

  .good_price{
    display: flex;
    font-size:14px;
    color:#E71F19;
    line-height: 6px;
    border-top: 1px #efefef solid;
  }
  .good_price del{
    color:#999;
  } 
  .good_price .cart{
    font-size: 20px;
    margin:10px 10px 10px 20px; 
    padding: 5px;
    border-radius:50%; 
    background: #E71F19;
  }
 
</style>
