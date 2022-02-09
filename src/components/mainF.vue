<template>
    <div class="section-container">

        <div class="center-text">
            <span class="sign">Artist coaching</span>
            <h1>Latest Online Courses</h1>
        </div>

        <div class="cards-container">
            <div class="card">
                <img src="../assets/images/artist-blog-01-480x356.jpg" >
            
                <div class="card-text-container">
                    <span class="price">$18.00</span>
                    <h3>The Acrylic Painting Academy</h3>
                    <i class="far fa-file-alt"></i><span>4 Lessons</span>
                    <i class="far fa-user"></i><span>50 Students</span>
                </div>
            </div>

            <div class="card">
            
            
                <div class="card-text-container">
                    <span class="price">$18.00</span>
                    <h3>The Acrylic Painting Academy</h3>
                    <i class="far fa-file-alt"></i><span>4 Lessons</span>
                    <i class="far fa-user"></i><span>50 Students</span>
                </div>
            </div>

            <div class="card">
                <img src="../assets/images/120012142_177596140500760_8623485824101406058_n.jpg" >
            
                <div class="card-text-container">
                    <span class="price">$18.00</span>
                    <h3>The Acrylic Painting Academy</h3>
                    <i class="far fa-file-alt"></i><span>4 Lessons</span>
                    <i class="far fa-user"></i><span>50 Students</span>
                </div>
            </div>

             <div class="card">
                
            
                <div class="card-text-container">
                    <span class="price">$18.00</span>
                    <h3>The Acrylic Painting Academy</h3>
                    <i class="far fa-file-alt"></i><span>4 Lessons</span>
                    <i class="far fa-user"></i><span>50 Students</span>
                </div>
            </div>
        </div>

         <div class="cards-container">
            <div class="card">
                
            
                <div class="card-text-container">
                    <span class="price">$18.00</span>
                    <h3>The Acrylic Painting Academy</h3>
                    <i class="far fa-file-alt"></i><span>4 Lessons</span>
                    <i class="far fa-user"></i><span>50 Students</span>
                </div>
            </div>

            <div class="card">
                <img src="../assets/images/120099363_364334431619755_7198812647386067017_n.jpg" >
            
                <div class="card-text-container">
                    <span class="price">$18.00</span>
                    <h3>The Acrylic Painting Academy</h3>
                    <i class="far fa-file-alt"></i><span>4 Lessons</span>
                    <i class="far fa-user"></i><span>50 Students</span>
                </div>
            </div>

            <div class="card">
                
            
                <div class="card-text-container">
                    <span class="price">$18.00</span>
                    <h3>The Acrylic Painting Academy</h3>
                    <i class="far fa-file-alt"></i><span>4 Lessons</span>
                    <i class="far fa-user"></i><span>50 Students</span>
                </div>
            </div>

             <div class="card">
                <img src="../assets/images/artist-event-01-250x300.jpg" >
            
                <div class="card-text-container">
                    <span class="price">$18.00</span>
                    <h3>The Acrylic Painting Academy</h3>
                    <i class="far fa-file-alt"></i><span>4 Lessons</span>
                    <i class="far fa-user"></i><span>50 Students</span>
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
    .section-container{
    width: 100%;
    height: 950px;
    border:1px solid red;
    
    .button-container{
        margin:20px auto;
        width: 50%;
        text-align: center; 
        button{
            background-color: rgba(253, 75, 75, 0.5);
            color:red;
            padding:5px 10px;
            border:none;
        }
    }

    .center-text{
        margin:20px auto;
        text-align: center;
    }
    .cards-container{
        width: 70%;
        margin:0 auto;
       
        display: flex;
        justify-content: space-between;

        .card{
            width: 24%;
            
            
            img{
                width: 100%;
            }
            .card-text-container{
                padding:20px;
                margin-bottom:20px;
                .price{
                    color:red;
                 
                }
                h3{
                    text-align: justify;
                    margin:10px 0;
                }
                span{
                    margin:0 5px;
                    margin-bottom:20px;
                    
                }
            }
        }

        
    }
}
</style>