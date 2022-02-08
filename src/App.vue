<template>
  <div id="app">
     <header-timeline/>
     <header-menu/>
  </div>
</template>

<script>

import headerTimeline from './components/headerTimeline.vue'
import headerMenu  from './components/headerMenu.vue'


export default {
  components: { 
    headerTimeline,
    headerMenu
  },
 
}
</script>,
    HeaderMenu

<style lang="scss">
  @import 'style/main.scss'
</style>
