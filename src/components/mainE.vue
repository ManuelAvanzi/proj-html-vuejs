<template>
     <div class="section-container">

        <div class="center-text">
            <span class="sign">Article and Tips</span>
            <h1>Latest From The Blog</h1>
        </div>

        <div class="cards-container">
          <div class="main-card">
              <div class="text-container">
                <div class="span">ARTIST</div>
                <h3>Connection Between self-Portrait and identity</h3>
                <i class="fa-regular fa-calendar"></i><span>May 15, 2020</span>
                <i class="fa-solid fa-eye"></i><span>397 views</span>
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
.section-container{
    width: 100%;
    height: 950px;
    
    background-color: rgba(177, 167, 167, 0.452);

    .cards-container{
        display: flex;
        justify-content: center;
        align-items: center;

        .main-card{
            display: flex;
            .text-container{
                align-self: flex-end;
            }

        width: 25%;
        height: 500px;
        
        background-image: url('../assets/images/artist-blog-02-500x680.jpg');
        background-size: cover;

        color:white;
        

    }

    
        
    }
    .center-text{
        margin:20px auto;
        text-align: center;
    }
}
</style>