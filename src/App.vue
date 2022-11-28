<script >
  import AppHeader from './components/AppHeader.vue';
  import AppMain from './components/AppMain.vue'
  import AppFootHeader from './components/AppFootHeader.vue';
  import AppFooterMain from './components/AppFooterMain.vue';
  export default{
    components:{
      AppHeader,
      AppMain,
      AppFootHeader,
      AppFooterMain
    }
  }
</script>

<template>
  <div >
    <AppHeader/>
    <AppMain/>
    <AppFootHeader/>
    <AppFooterMain/>
  </div>
  
</template>

<style lang="scss">
  @import './style/global.scss'
</style>
