<template>
    <div class="section-container">
        <div class="box left-section">
            <h3>Adress</h3>
            <span>
                382 NE 191st # 87394 Miami, Fl 33179-3899
                +1(305) 547-9909 (9am - 5pm EST, Monday - Friday)
                support@maxcoach.com
            </span>
            <div class=" social-container">
                <i class="fab fa-twitter"></i>
                <i class="fab fa-facebook-f"></i>
                <i class="fab fa-instagram"></i>
                <i class="fab fa-linkedin"></i>
            </div>

        </div>

        <div class="box middle-section">
            <div class="list-container">
                <ul>
                    <li><h3>Explore</h3></li>
                    <li v-for="(link, index) in exploreList" :key="index">{{link}}  </li>               
               </ul>
            </div>
            <div class="list-container">
                <ul>
                    <li><h3>Information</h3></li>
                    <li v-for="(link, index) in informationList" :key="index">{{link}}  </li>               
                </ul>
            </div>
            
            
            
        </div>

        <div class="box right-section">
            <span>Instagram</span> <span id="orange">@maxcoach</span>
            <div class="pics-container">
                <img src="../assets/images/artist-blog-01-480x356.jpg">
                <img src="../assets/images/120012142_177596140500760_8623485824101406058_n.jpg">
                <img src="../assets/images/120099363_364334431619755_7198812647386067017_n.jpg">
                
            </div>
        </div>
    </div>
</template>


<script>
export default {
    props:{
      exploreList: Array,
      informationList: Array,

  }
}
</script>



<style lang="scss" scoped>
@import '@/style/variables.scss';
@import '@/style/footerStyle/footerB.scss';

</style>