<template>
  <div class="me">
    <NavBar></NavBar>
    <!-- <Login></Login> -->
    <Register></Register>
    
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
 import NavBar from '@/components/NavBar.vue'
//  import Login from '@/components/Login.vue'
 import Register from '@/components/Register.vue'
 


export default {
  name: 'me',
  components: {
    NavBar,
    // Login,
    Register
  }
}
</script>

<style scoped>
  .me{
    height: 100vh;
    width: 100%;
    background: #f2f2f2;
  }
 
</style>
