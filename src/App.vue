<script >
  
  import AppNav from './components/AppNav.vue'
  import AppLoader from './components/AppLoader.vue'


  export default {
  components:{  AppNav, AppLoader }
  }
</script>

<template>

  <div class="container">
    <AppNav class="appnav"/>
    <router-view class="page"></router-view>
    <AppLoader />
  </div>
 

  
</template>

<style lang="scss">
@use './assets/styles/general.scss' as *;


.appnav{
  width: 100vw;
  position: relative;
  z-index: 200;
}




@media (max-width:1100px) {
    
    
}



</style>
