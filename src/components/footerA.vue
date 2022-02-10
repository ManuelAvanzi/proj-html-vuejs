<template>
    <div class="section-container">
        <div class="stripe-container">
            
            <div class="left-side">
                <h1>Newsletter to get in touch</h1>
            </div>
            <div class="right-side">
                <span>Your e-mail</span><i class="fa-solid fa-arrow-right-long"></i>
                
                <hr>
                
            </div>
            <img src="../assets/images/artist-shape-color-paint-bottom-right.png" alt="">

        </div>
    </div>
</template>


<script>
export default {
    
}
</script>



<style lang="scss" scoped>
@import '@/style/variables.scss';

     .section-container{
         width: 100%;
         height: 180px;

         .stripe-container{
             width: 100%;
             height:180px;
             display: flex;
             justify-content: center;
             align-items: center;
             background-color: $blue;
             .left-side{
                 margin:0 30px;
                 color:white;
             }
         }
     }

</style>