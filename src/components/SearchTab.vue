<template>
  <div class="searchtab">
    <form action="/">
      <van-search
        v-model="value"
        placeholder="请输入搜索关键词"
        show-action
        @search="onSearch"
      />
    </form>
    
  </div>
</template>

<script>
export default {
  name: 'SearchTab',
  data () {
    return {
      value:''
    }
  },

  props: {
    
  },
  methods:{
    onSearch(){
      
    }
   
  } 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
 
</style>
