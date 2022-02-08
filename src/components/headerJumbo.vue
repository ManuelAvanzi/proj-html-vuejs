<template>
    <div class="jumbotron-container">
        <div class="img-container">
            
            <img src="../assets/images/artist-hero-image-02.jpg" class="hero-image first" alt="">
            <img src="../assets/images/artist-hero-image-01.jpg" class="hero-image second" alt="">
            <img src="../assets/images/artist-hero-image-04.jpg" class="hero-image third" alt="">

            <div class="text-container">
                <div class="hello"><span>Hello, im Matin</span></div>
                <div class="main-text">
                    <h1>Artist Coaching And Mentoring Might Be For You</h1>
                    <button>get started today</button>
                </div>
            </div>
            
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>


<style lang="scss" scoped>
   .jumbotron-container{
       width: 100%;
       height: 450px;
       background-color: pink;
       position:absolute;

       .text-container{
           border:1px solid grey;
           width: 300px;
           margin:0 auto;
           text-align: center;
       }

       .hero-image{
           position:relative;
           width: 180px;
       }
       .first{
           
           top:50px;
           left:300px;
       }
       .second{
           top:200px;
           left:10px;
       }
       .third{
           top:180px;
           left:650px;
       }
   }
   
</style>