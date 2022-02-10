<template>
    <div class="jumbotron-container">
        <div class="img-container">
            
            <img src="../assets/images/artist-hero-image-02.jpg" class="hero-image first" alt="">
            <img src="../assets/images/artist-hero-image-01.jpg" class="hero-image second" alt="">
            <img src="../assets/images/artist-hero-image-04.jpg" class="hero-image guy" alt="">
            <img src="../assets/images/artist-hero-image-03.png" class=" face" alt="">
            <img src="../assets/images/artist-shape-04.png" class="shape piuma" alt="">
            <img src="../assets/images/artist-shape-03.png" class="shape rotate dots" alt="">
            <img src="../assets/images/artist-shape-02.png" class="shape left-top" alt="">
            <img src="../assets/images/artist-shape-01.png" class="shape leaf" alt="">
            <img src="../assets/images/artist-shape-05.png" class="shape colors" alt="">

            <div class="text-container">
                <div class="hello"><span class="sign">Hello, im Matin</span></div>
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
@import '@/style/variables.scss';
   .jumbotron-container{
       width: 100%;
       height: 700px;
       border:1px solid black;
       background-color: #fbf9f6;
       position:relative;
       
       .left-top{
           position:absolute;
           top:0;
           left:0;
       }
       .piuma{
           position:absolute;
           top:40px;
           width: 100px;
           right:130px;
       }
       .leaf{
           position:absolute;
           top:0;
           right:120px;
           width:400px;
       }
       .face{
           position:absolute;
           bottom:10px;
           left:290px;
           width: 150px;
       }
      
       .dots{
           position:absolute;
           left:30px;
           top:60px;
           width: 200px;
           transform: rotateY('90');
       }
       .colors{
           position:absolute;
           bottom:0;
           right:20px;
       }

       .text-container{
           border:1px solid grey;
           width: 300px;
           margin:0 auto;
           text-align: center;
           .sign{
                   font-family: "Rossela Demo", Sans-serif;
                    font-size: 64px;
                    font-weight: 400;
                    color: $cerulean;
                }
           }
       }

       .hero-image{
           position:relative;
           width: 180px;
            box-shadow: 0 3px 10px rgb(0 0 0 / 0.2);
       }
       .first{
           z-index: 1231;
           top:50px;
           left:300px;
       }
       .second{
           top:200px;
           left:10px;
       }
       .guy{
           z-index: 1231;
           top:180px;
           left:650px;
           width:270px;
       }
   
   
</style>