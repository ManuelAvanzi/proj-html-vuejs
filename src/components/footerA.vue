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

        </div>
    </div>
</template>


<script>
export default {
    
}
</script>



<style lang="scss" scoped>

     .section-container{
         width: 100%;
         height: 180px;

         .stripe-container{
             width: 100%;
             height:180px;
             display: flex;
             justify-content: center;
             align-items: center;
             background-color: rgba(15, 15, 158, 0.481);
             .left-side{
                 margin:0 30px;
                 color:white;
             }
         }
     }

</style>