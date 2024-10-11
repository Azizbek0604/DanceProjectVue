<script>
import Bike from '@/images/bike.svg'

export default{
    data(){
        return{
            Bike
        }
    }
}
</script>

<template>
    <div class="AllIn">
        <h1 class="h1tag">Move Your Way</h1>
        <p class="ptag">Choose the electric ride that suits your lifestyle.</p>
        <div class="container">
            <div class="post">
                <img class="img" :src="Bike" alt="bike">
                <div class="lineOne">
                    <p class="lineP">From €59 to €39/mo</p>
                    <button class="lineB">Winner offer</button>
                </div>
                <h3 class="postH">Dance One Step</h3>
                <p class="postP">Ebike</p>
                <button class="postB">See details</button>
            </div>

            <div class="post">
                <img class="img" :src="Bike" alt="bike">
                <div class="lineOne">
                    <p class="lineP">From €59 to €39/mo</p>
                    <button class="lineB">Winner offer</button>
                </div>
                <h3 class="postH">Dance One Step</h3>
                <p class="postP">Ebike</p>
                <button class="postB">See details</button>
            </div>

            <div class="post">
                <img class="img" :src="Bike" alt="bike">
                <div class="lineOne">
                    <p class="lineP">From €59 to €39/mo</p>
                    <button class="lineB">Winner offer</button>
                </div>
                <h3 class="postH">Dance One Step</h3>
                <p class="postP">Ebike</p>
                <button class="postB">See details</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.postH{
    font-size: 29px;
    font-weight: 400;
    padding-left: 17px;
    padding-top: 20px;
}
.postP{
    font-size: 18px;
    font-weight: 400;
    padding-left: 17px;
}
.postB{
    margin-top: 20px;
    width: 180px;
    margin-left: 67px;
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
    border: none;
}
.lineOne{
    display: flex;
    align-items: center;
    padding-top: 8px;
}
.lineB{
    font-size: 16px;
    font-weight: 400;
    border-radius: 15px;
    width: 100px;
    border: none;
    height: 25px;
    color: #7140EB;
    cursor: pointer;
    transition: transform 0.3s ease, background 0.3s ease;  
}
.lineB:hover {
    transform: scale(1.1); 
    background: #5a30c7; 
    color: gold;
}
.lineP{
    font-size: 17px;
    font-weight: 400;
}
.AllIn{
    min-height: 100vh; 
    background: #F5F5F7;
    padding-top: 50px;
    padding-left: 70px;
    
}
.container{
    display: flex;
    align-items: center;
}
.h1tag{
    font-size: 67px;
    font-weight: 400;
    color: #2E2C34;
    padding-left: 100px;
}
.ptag{
    font-size: 20px;
    font-weight: 400;
    color: #2E2C34;
    padding-top: 20px;
    padding-left: 100px;
}
.post{
    border: 1px solid black;
    border-radius: 10px;
    border: none;
    background: #fff;
    margin-top: 60px;
    width: 320px;
    height: 450px;
    transition: transform 0.3s ease, background 0.3s ease;  
}
.post:hover {
    transform: scale(1.1); 
}
.img{
    margin-top: 20px
}
</style>