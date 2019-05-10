<template>
  <div id="app">
   <appnav></appnav>
    
    <router-view class="container"/>
  </div>
</template>
<script>
import appnav from '@/components/appnav';
export default {
  components:{
    appnav,
  },
}
</script>

<style lang="scss">
</style>
