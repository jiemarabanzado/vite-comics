<script >
  import AppHeader from './components/AppHeader.vue';
  import AppMain from './components/AppMain.vue'
  import AppFootHeader from './components/AppFootHeader.vue';
  export default{
    components:{
      AppHeader,
      AppMain,
      AppFootHeader
    }
  }
</script>

<template>
  <div >
    <AppHeader/>
    <AppMain/>
    <AppFootHeader/>
  </div>
  
</template>

<style lang="scss">
  @import './style/global.scss'
</style>
