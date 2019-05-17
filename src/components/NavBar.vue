<template>
  <div class="navbar">
    <van-nav-bar
    title="标题"
    left-text="返回"
    right-text="按钮"
    left-arrow
    @click-left="onClickLeft"
    @click-right="onClickRight"
    />

    
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  data () {
    return {
      active: 0
    }
  },

  props: {
    
  },
  
  methods: {
    // onClickLeft() {
    // Toast('返回');
    // },
    // onClickRight() {
    // Toast('按钮');
    // }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 
 
</style>
