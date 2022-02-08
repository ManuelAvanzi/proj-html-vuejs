<template>
  <div id="app">
     <header-timeline/>
     <header-menu/>
     <header-jumbo/>
     <main-a/>
  </div>
</template>

<script>

import headerTimeline from './components/headerTimeline.vue'
import headerMenu  from './components/headerMenu.vue'
import HeaderJumbo from './components/headerJumbo.vue'
import MainA from './components/mainA.vue'


export default {
  components: { 
    headerTimeline,
    headerMenu,
    HeaderJumbo,
    MainA
  },
 
}
    
</script>,
,
    HeaderJumbo    HeaderMenu

<style lang="scss">
  @import 'style/main.scss'
</style>
