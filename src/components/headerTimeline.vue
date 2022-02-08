<template>
    <div class="container">
        <span>starts TOMORROW! Our biggest event of the year...
            <i class="far fa-clock"></i>
            <span class="time-zero">00:00:00:00</span>
            <button class="button">get ticket</button>
        </span>
    </div>
</template>


<script>
export default {
    
}
</script>


<style lang="scss" scoped>
.container{
    width:100%;
    height: 40px;
    background-color: rgba(128, 128, 128, 0.863);
    display: flex;
    justify-content: center;
    align-items: center;
    

    span{
        color:rgb(70, 70, 70);
        margin:0 20px;
    }
    button{
        color:white;
        padding:4px 10px;
        background-color: orange;
        border-radius: 5px;
        border-color:none;
    }
}
</style>