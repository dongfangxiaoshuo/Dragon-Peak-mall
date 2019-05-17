<template>
  <div class="showpictures">
    <div >
      <div class="img_one">
        <a href="#"><img src="../../public/img/index/20180510neesok.png" alt=""></a>
      </div>
      <div class="img_two">
        <img src="../../public/img/index/10673243_thumb_G_1517475594696.jpg" alt="">
        <img src="../../public/img/index/10673241_thumb_G_1517473718540.jpg" alt="">
        <img src="../../public/img/index/10669274_thumb_G_1509270440136.jpg" alt="">
        <img src="../../public/img/index/10669238_thumb_G_1509249330952.jpg" alt="">
      </div>
    </div>
    <div class="img_wrap">

      <div class="img_wrap_left">
        <img src="../../public/img/index/parta_new.jpg" alt="">
        <img src="../../public/img/index/partc_new.jpg" alt="">
      </div>

      <div class="img_wrap_right">
        <img src="../../public/img/index/partb1_new.jpg" alt="">
        <img src="../../public/img/index/partb2_new.jpg" alt="">
        <img src="../../public/img/index/partb3_new.jpg" alt="">
      </div>


    </div>
    
   
  </div>
</template>

<script>
export default {
  name: 'Showpictures',
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
  .showpictures{
    padding: 10px 10px;
  }
  .img_one{
    border-radius: 12px;
    width: 100%;
  }
  .img_one img{
    width: 100%;
  }
  .img_two{
    display: flex;
    justify-content:space-around;
    width: 100%;
  }
  .img_two img{
    height: 5.3rem;
    width: 5.3rem;
  }
  .img_wrap{
    display: flex;
    margin-top:10px; 
  }
  .img_wrap .img_wrap_left{
    display: flex;
    flex-direction:column;
  }
  .img_wrap img{
    width: 100%;

  }
  .img_wrap .img_wrap_right{
    display: flex;
    flex-direction:column;
  }

 
</style>
