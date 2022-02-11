<template>
    <div class="menu-container">
       <div class="logo-container" >
           <img src="../assets/images/dark-logo.png" alt="logo">
       </div>


       <div class="nav-container">
           <ul>
                <li v-for="(link, index) in menuList" :key="index">{{link}} <i class="fas fa-chevron-down"></i> </li>               
           </ul>
       </div>

       <div class="social-container">
           <i class="fab fa-twitter"></i>
           <i class="fab fa-facebook-f"></i>
           <i class="fab fa-instagram"></i>
           <i class="fab fa-linkedin"></i>
       </div>
    </div>
</template>


<script>
export default {
  props:{
      menuList: Array,

  }
}
</script>


<style lang="scss" scoped>
@import '../style/headerStyle/headermenu.scss';
@import '../style/variables.scss';

</style>