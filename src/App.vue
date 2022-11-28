<script >
  import AppHeader from './components/AppHeader.vue';
  import AppMain from './components/AppMain.vue'
  import AppFootHeader from './components/AppFootHeader.vue';
  import AppFooterMain from './components/AppFooterMain.vue';
  import AppFooter from './components/AppFooter.vue';
  export default{
    components:{
      AppHeader,
      AppMain,
      AppFootHeader,
      AppFooterMain,
      AppFooter
    }
  }
</script>

<template>
  <div >
    <AppHeader/>
    <AppMain/>
    <AppFootHeader/>
    <AppFooterMain/>
    <AppFooter/>
  </div>
  
</template>

<style lang="scss">
  @import './style/global.scss'
</style>
