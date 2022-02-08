<template>
  <div id="app">
     <header-timeline/>
     <header-menu/>
     <header-jumbo/>
     <main-a/>
     <main-b/>
     <main-c/>
     <main-d/>
  </div>
</template>

<script>

import headerTimeline from './components/headerTimeline.vue'
import headerMenu  from './components/headerMenu.vue'
import HeaderJumbo from './components/headerJumbo.vue'
import MainA from './components/mainA.vue'
import MainB from './components/mainB.vue'
import MainC from './components/mainC.vue'
import MainD from './components/MainD.vue'



export default {
  components: { 
    headerTimeline,
    headerMenu,
    HeaderJumbo,
    MainA,
    MainB,
    MainC,
    MainD
    
  },
 
}
    
</script>,
,
    HeaderJumbo    HeaderMenu

<style lang="scss">
  @import 'style/main.scss'
</style>
