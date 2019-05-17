<template>
  <div class="search">
    <NavBar></NavBar>
    <SearchTab></SearchTab>
    <SearchHistory></SearchHistory>

    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
 import NavBar from '@/components/NavBar.vue'
 import SearchTab from '@/components/SearchTab.vue'
 import SearchHistory from '@/components/SearchHistory.vue'


export default {
  name: 'search',
  components: {
    NavBar,
    SearchTab,
    SearchHistory
  }
}
</script>
