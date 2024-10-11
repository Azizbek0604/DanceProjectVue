<script>
import Img from '@/images/girlbike.svg'

export default{
    data(){
        return{
            Img
        }
    }
}
</script>

<template>
    <div class="container">
        <div class="textSide">
            <h1 class="textH">Just ride — <br>we’ll take care <br> of the rest</h1>
            <p class="textP">Your local Concierge Team will repair or replace your ride within 24 hours—all included with your subscription.</p>
            <button class="postB">See details</button>
        </div>

        <div class="imgSide">
            <img class="imgSi" :src="Img" alt="img">
        </div>
    </div>
</template>

<style  scoped>
.textSide{
    padding-left: 150px;
}
.container{
    min-height: 80vh;
    background: #F5F5F7;
    display: flex;
    padding-top: 100px;
}
.imgSi{
    width: 797px;
    height: 378px;
}
.textH{
    font-size: 67px;
    font-weight: 400;
}
.textP{
    font-size: 18px;
    font-weight: 400;
    padding-top: 20px;
}
.postB{
    margin-top: 20px;
    width: 180px;
    height: 61px;
    border-radius: 999px;
    background: #fff;
    font-size: 16px;
    font-weight: 400;
    transition: transform 0.3 ease, background 0.3 ease;
    cursor: pointer;
}
.postB:hover{
    transform: scale(1.1);
    background: #5a30c7; 
    color: gold;
}
</style>