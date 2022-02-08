<template>
    <div>
        <div class="container-b">

          <div class="left-side">
               <img src="../assets/images/artist-quote-icon.png" alt="">
              <h1>I coach and mentor visual artists,like you, to Create like you Mean it</h1>
              <span class="sign light-blue">Martin Garrix</span>
          </div>
          <div class="right-side">
              <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Totam, illum aliquid ex earum vitae tempora ad eos numquam corrupti perspiciatis consequuntur blanditiis doloribus ipsam temporibus iure voluptatem quibusdam. Est, sit!</p>
              <br>
              <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. </p>
              <button class>Get started today</button>
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
.quote{
        
        width: 35%;
        
        margin:0 auto;
    }
.container-b{
    width: 70%;
    height: 400px;
    
    margin:0 auto;
    display: flex;
    

    
    .left-side{
        padding:50px;
        width:50%;
        text-align: center;
        
        .light-blue{
            
            font-size: 33px;
            color:$cerulean;
            
        }
    }
    .right-side{
        padding:50px;
        width:50%;
        margin-top:43px;
        text-align: justify;

        button{
            color:rgba(228, 4, 4, 0.836);
            background-color: rgba(255, 0, 0, 0.521);
            padding:5px 10px;
            border-radius:5px;
            border-color:white;
            margin-top:20px;
        }
    }
}
</style>