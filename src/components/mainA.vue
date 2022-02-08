<template>
    <div class="container-a">
        
        <div class="text-container">
            <span class="light-blue">Artist Coaching</span>
            <h1 class="main-text">I understand what it takes to create. I can help you with</h1>
        </div>

        <div class="four-boxes">
            <div class="box a">

                <div class="box-pic">
                    <img src="../assets/images/artist-box-image-01.png" alt="">
                </div>

                <h1 class="box-title">Online Courses</h1>

                <div class="box-text">
                    online art coaching now offers you a very powerfull way to redesign your artist mind
                </div>
            </div>

            <div class="box b">

                <div class="box-pic">
                    <img src="../assets/images/artist-box-image-02.png" alt="">
                </div>

                <h1 class="box-title">One to one</h1>

                <div class="box-text">
                    online art coaching now offers you a very powerfull way to redesign your artist mind
                </div>
            </div>

            <div class="box c">

                <div class="box-pic">
                    <img src="../assets/images/artist-box-image-03.png" alt="">
                </div>

                <h1 class="box-title">Anywhere</h1>

                <div class="box-text">
                    online art coaching now offers you a very powerfull way to redesign your artist mind
                </div>
            </div>

            <div class="box d">

                <div class="box-pic">
                    <img src="../assets/images/artist-box-image-04.png" alt="">
                </div>

                <h1 class="box-title">On Time</h1>

                <div class="box-text">
                    online art coaching now offers you a very powerfull way to redesign your artist mind
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
.container-a{
   width: 100%;
   
   .text-container{
       
       width: 300px;
       margin:20px auto;
       border:1px solid grey;
       text-align: center;

       .ligh-blue{
           color:$cerulean;
       }
   }

   .four-boxes{
       
       width: 70%;
       height: 500px;
       margin:0 auto;
       display: flex;

       .box{
           
           width: 25%;

           .box-text{
               padding-right:20px;
           }

       }
       .b{
           margin-top:30px;
       }
       .d{
           margin-top:60px;
       }
   }
}
</style>