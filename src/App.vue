<template>
  <div id="app">
     <header-timeline/>
     <header-menu :menuList="this.menuList"/>
     <header-jumbo/>
     <main-a/>
     <main-b/>
     <main-c/>
     <main-d/>
     <main-e/>
     <main-f/>
     <footer-a/>
     <footer-b :exploreList="this.exploreList" :informationList="this.informationList"/>
     
  </div>
</template>

<script>

import headerTimeline from './components/headerTimeline.vue'
import headerMenu  from './components/headerMenu.vue'
import HeaderJumbo from './components/headerJumbo.vue'

import MainA from './components/mainA.vue'
import MainB from './components/mainB.vue'
import MainC from './components/mainC.vue'
import MainD from './components/mainD.vue'
import MainE from './components/mainE.vue'
import MainF from './components/mainF.vue'

import FooterA from './components/footerA.vue'
import FooterB from './components/footerB.vue'





export default {
  name: 'App',
  components: { 
    headerTimeline,
    headerMenu,
    HeaderJumbo,
    MainA,
    MainB,
    MainC,
    MainD,
    MainE,
    MainF,
    FooterA,
    FooterB
  },

  data() {
    return {
      
      //header menu 

      menuList: [
        'Home',
        'Pages',
        'Courses',
        'Features',
        'Blog',
        'Shop',
      ],

      //footer list 
      exploreList: [
        'Start here',
        'Success story',
        'Blog',
        'Courses',
        'About us',
        'Contact us'
      ],
      informationList: [
        'Membership',
        'Puchase guide',
        'Privacy policy',
        'Terms of services'
      ],
    }
  }
 
}
    
</script>,
,
    HeaderJumbo    HeaderMenu

<style lang="scss">
  @import 'style/main.scss'
</style>
