<template>
  <div id="app">
     <timeline-bar/>
  </div>
</template>

<script>

import timelineBar from './components/timelineBar.vue'

export default {
  components: { 
    timelineBar 
  },
 
}
</script>

<style lang="scss">
  @import 'style/main.scss'
</style>
