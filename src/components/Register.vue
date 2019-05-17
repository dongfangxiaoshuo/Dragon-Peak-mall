<template>
  <div class="register">

    <div class="register_wrap">
      <van-cell-group>
      <van-field
        v-model="phone"
        label="手机号"
        placeholder="请输入手机号"
        required
        error-message=""
      />
      <van-field
        v-model="password"
        label="密码"
        placeholder="请输入密码"
        required
        error-message=""
      />
      <van-field
        v-model="shortMessage"
        label="短信验证码"
        placeholder="请输入短信验证码"
        required
        error-message=""
      />
      <div class="getshortmessage">
        <van-button round type="danger" size="small">获取短信验证码</van-button>
      </div>
     
    </van-cell-group>

    </div>
    
    <div class="register_button">
      <van-button size="large" type="danger">注册</van-button>
    </div>

    
  </div>
</template>

<script>
export default {
  name: 'Register',
  data () {
    return {
      phone:'',
      password:'',
      shortMessage:''
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
   .register{
    position: relative;
    padding: 2rem 1rem 1rem 1rem;
  }
  .register_wrap{
    padding-bottom: 1.5rem;
  }
  .getshortmessage{
    position: absolute;
    top: 6rem;
    right: 1rem;
  }
  .register_button{
    padding: 0 0rem 1.5rem 0rem;
  }
 
 
</style>
