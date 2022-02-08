<template>
    <div class="section-container">
        <div class="youtube-section">
           <img src="../assets/images/icon-youtube-play.png" alt="">
        </div>

        <div class="center-text">
            <span class="testimonials">Testimonials</span>
            <h1>Why do people love me ?</h1>
        </div>

        <div class="slider-section">
            <div class="left">
                <h3>High level of efficiency and scientific teaching methods</h3>
                 <span>I am free to learn at my own pace, follow my own schedules and choose the subject i want to learn from the syllabus.Great study portal for people like me.</span>
            </div>
            <div class="middle">
                <h3>High level of efficiency and scientific teaching methods</h3>
                 <span>I am free to learn at my own pace, follow my own schedules and choose the subject i want to learn from the syllabus.Great study portal for people like me.</span>
            </div>
            <div class="right">
                <h3>High level of efficiency and scientific teaching methods</h3>
                 <span>I am free to learn at my own pace, follow my own schedules and choose the subject i want to learn from the syllabus.Great study portal for people like me.</span>
            </div>
        </div>

        <div class="navigator">
            <ul>
                <li><i class="fas fa-circle"></i></li>
                <li><i class="fas fa-circle"></i></li>
                <li><i class="fas fa-circle"></i></li>
            </ul>
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
    
    height: 850px;

    .youtube-section{
        margin:0 auto;

        width: 45%;
        height: 320px;
        background-image: url('../assets/images/artist-video-poster.jpg');
        background-size: contain;
        display: flex;
        justify-content: center;
        align-items: center;
        
        img{
            width: 70px;
        }
        
    }

    .center-text{

        margin:50px auto;
        text-align: center;
        .testimonials{
            color:$cerulean;
        }
    }
    .slider-section{
        width: 80%;
        height: 300px;
        
        margin:0 auto;

        display: flex;
        justify-content: space-between;

        .left,.middle,.right{

            width: 30%;
            background-color: rgba(187, 178, 178, 0.644);
            
            text-align: justify;
            padding:10px;
            h3{
                margin-bottom:20px;
            }

        }
    }
    .navigator{
        margin:10px auto;
        
        width: 200px;

        ul{
            display: flex;
            justify-content: center;
            li{
                margin-right:5px;
                list-style: none;
                cursor: pointer;
            }

        }
    }
}
</style>