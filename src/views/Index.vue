<template>
  <div class="index">
    <HeardSearch></HeardSearch>
    <Nav></Nav>
    <Headlines></Headlines>
    <ShowPictures></ShowPictures>
    <Good></Good>
    <!-- <Tabber></Tabber> -->
    <FootNav></FootNav>

    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
 import HeardSearch from '@/components/HeardSearch.vue'
 import Nav from '@/components/Nav.vue'
 import Headlines from '@/components/Headlines.vue'
 import ShowPictures from '@/components/ShowPictures.vue'
 import Good from '@/components/Good.vue'
//  import Tabber from '@/components/Tabber.vue'
 import FootNav from '@/components/FootNav.vue'


export default {
  name: 'index',
  components: {
    HeardSearch,
    Nav,
    Headlines,
    ShowPictures,
    Good,
    // Tabber
    FootNav
  }
}
</script>
