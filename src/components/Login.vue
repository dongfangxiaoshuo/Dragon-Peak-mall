<template>
  <div class="login">
    <div class="login_wrap">
      <van-cell-group>
        <van-field
          v-model="username"
          required
          clearable
          label="用户名"
          right-icon="question-o"
          placeholder="请输入用户名"
          @click-right-icon="$toast('question')"
        />

        <van-field
          v-model="password"
          type="password"
          label="密码"
          placeholder="请输入密码"
          required
        />
      </van-cell-group>
    </div>

    <div class="login_button">
      <van-button size="large" type="danger">登陆</van-button>
    </div>

    <div class="login_radio">
      <van-radio checked-color="#ff2233" class="radio">自动登陆</van-radio>
      <div class="login_href">
        <a href="#">免费注册</a>
        <a href="#">忘记密码</a>
      </div>
    </div>


    <div class="third-area">
      <div class="third-area-a"><font color="#d8d8d8">————</font>&nbsp;第三方登录&nbsp;<font color="#d8d8d8">————</font></div>
      <a class="ta-qq" href="user.php?act=connectqq" title="QQ"><i class="&#xe646;"></i></a>
<!--                <a class="ta-weibo" href="user.php?act=oath&type=weibo" title="weibo"></a>-->
      <a class="ta-weixin" href="user.php?act=connectwechat" title="weixin"></a>
    </div>

    <i class="iconfont &#xe646;"></i>
    <i class="&#xe66a;"></i>
  </div>
</template>

<script>
export default {
  name: 'Login',
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
  .login{
    position: relative;
    padding: 2rem 1rem 1rem 1rem;
  }
  .login_wrap{
    padding-bottom: 1.5rem;
  }
  .login_button{
    padding: 0 0rem 1.5rem 0rem;
  }
  .radio{
    position: absolute;
    left: 1rem;
  }
  .login_href{
    position: absolute;
    top: 14rem;
    right: 1rem;
  }
  .login_href a{
    font-size: 14px;
    padding: 0.3rem;
  }
  .third-area{
    padding-top:4rem; 
  }

 
</style>
