<script>
import Moto from '@/images/moto.svg'
import Bike from '@/images/bike.svg'

export default{
    data(){
        return{
            Moto,
            Bike,
        }
    }
}
</script>

<template>
    <div class="container">
        <div class="leftSide">
            <h1 class="leftH">You’re in <br> charge</h1>
            <p class="leftP">Your subscription is fully <br> flexible—with free <br> cancelation at any time <br> and no sign-up fees.</p>
            <div class="button-container">
                <button class="btn">Repairs within 24 hours</button>
                <button class="btn">Replacements in case of theft</button>
                <button class="btn">App to track your rides</button>
                <button class="btn">Cancel anytime</button>
            </div>
        </div>

        <div>
            <div class="Posts">
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
.lineOne{
    display: flex;
    align-items: center;
    padding-top: 8px;
}
.postB:hover{
    transform: scale(1.1);
    background: #5a30c7; 
    color: gold;
    border: none;
}
.button-container {
    display: grid;
    grid-template-columns: 1fr;
    gap: 15px; 
    margin-top: 50px;
}
.button-container button {
    width: 100%; 
    background: #F5F5F7;
    height: 37px;
    border-radius: 40px;
    border: none;
    transition: transform 0.3 ease, background 0.3 ease;
    cursor: pointer;
}
button:hover{
    transform: scale(1.1);
    background: #5a30c7; 
    color: gold;
}
.Posts{
    display: flex;
}
.leftH{
    font-size: 65px;
    font-weight: 400;
}
.leftP{
    font-size: 21px;
    font-weight: 400;
}
.container{
    min-height: 100vh;
    display: flex;
    padding-top: 150px;
}
.post{
    border: 1px solid black;
    border-radius: 10px;
    margin-left: 30px;
    background: #F5F5F7;
    margin-top: 60px;
    width: 320px;
    height: 450px;
    transition: transform 0.3s ease, background 0.3s ease;  
}
.post:hover {
    transform: scale(1.1); 
}
</style>