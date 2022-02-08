<template>
    <div class="menu-container">
       <div class="logo-container">
           <img src="../assets/images/dark-logo.png" alt="logo">
       </div>


       <div class="nav-container">
           <ul>
               <li>Home<i class="fas fa-chevron-down"></i></li>
               <li>Pages<i class="fas fa-chevron-down"></i></li>
               <li>Courses<i class="fas fa-chevron-down"></i></li>
               <li>Features<i class="fas fa-chevron-down"></i></li>
               <li>Blog<i class="fas fa-chevron-down"></i></li>
               <li>Shop<i class="fas fa-chevron-down"></i></li>
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

}
</script>


<style lang="scss" scoped>
@import '@/style/variables.scss';
.menu-container{
    width: 100%;
    height: 70px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    border:1px solid green;


    .logo-container{
        
        
        img{
            width: 200px;
        }
    }

    .nav-container{
        
       
        
        ul{
            display: flex;
            list-style: none;
            
            li{
                padding:10px;
                cursor: pointer;
                margin-right:2px;
                    
                 &:hover{
                    color:$blue; 
                 }
                 .fas,.fa-chevron-down{
                     width: 10px;
                     
                     padding:0 3px;
                 }
               }
        }
    }

    .social-container{
        
        .fa-twitter,.fa-facebook-f,.fa-linkedin,.fa-instagram{
            font-size: 30px;
            width: 30px;
            padding:5px;
        }
        
    }
   
        
    
    
    
    
}
</style>