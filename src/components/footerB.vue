<template>
    <div class="section-container">
        <div class="left-section">
            <h3>Adress</h3>
            <span>
                382 NE 191st # 87394 Miami, Fl 33179-3899
                +1(305) 547-9909 (9am - 5pm EST, Monday - Friday)
                support@maxcoach.com
            </span>
            <div class="social-container">
                <i class="fab fa-twitter"></i>
                <i class="fab fa-facebook-f"></i>
                <i class="fab fa-instagram"></i>
                <i class="fab fa-linkedin"></i>
            </div>

        </div>

        <div class="middle-section">
            <ul>
                <li>Start here</li>
                <li>Start here</li>
                <li>Start here</li>
                <li>Start here</li>
                <li>Start here</li>
            </ul>
            <ul>
                <li>Start here</li>
                <li>Start here</li>
                <li>Start here</li>
                <li>Start here</li>
                <li>Start here</li>
            </ul>
        </div>

        <div class="right-section">
            <h3>Instagram</h3><span>@maxcoach</span>
            <div class="pics-container">
                <img src="../assets/images/artist-event-01-250x300.jpg">
                <img src="../assets/images/artist-event-01-250x300.jpg">
                <img src="../assets/images/artist-event-01-250x300.jpg">
                
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
    width:100%;
    height:400px;
    border:1px solid green;
    display: flex;

    .left-section{
        width: 30%;
        border:1px solid red;
    }
    .middle-section{
        width:30%;
        border:1px solid blue;
        display: flex;
    }
    .right-section{
        .pics-container{
           
           display: flex;
           justify-content: center;

           img{
               width:150px;
               height:150px;
               margin:10px;
           }
        

        
        
            
        }
       
    }
}

</style>