<script>
import motobike from '@/images/bikemoto.svg'

export default{
    data() {
        return{
            motobike
        }
    }
}
 </script>

<template>
    <div class="container">
        <h1 class="h1text">How it works</h1>
        <div class="allIn">
            <div class="texts">
                <p>1. Pick your city</p>
                <br>
                <p>2. Choose your ride</p>
                <br>
                <p>3. Delivery  </p>
                <br>
                <p>4. Ride freely</p>
    
                <button class="btn">StraT now</button>
            </div>
    
            <div class="img">
                <img :src="motobike" alt="motobike">
            </div>
        </div>
    </div>
</template>

<style scoped>
.btn{
    margin-top: 100px;
}
.btn {
    margin-left: 50px;
    background: #7140EB;
    border: none;
    width: 183px;
    height: 42px;
    border-radius: 999px;
    cursor: pointer;
    color: #fff;
    font-weight: 400;
    font-size: 18px;
    transition: transform 0.3s ease, background 0.3s ease;  
}

.btn:hover {
    transform: scale(1.1); 
    background: #5a30c7; 
    color: gold;
}
.container{
    min-height: 100vh; 
    background: #fff;
}
.img{
    margin-left: 400px;
}
.texts{
    padding-top: 50px;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap; 
    font-weight: 400;
    font-size: 28px;   
    margin-left: 144px;
}
.allIn{
    display: flex;
    margin-top: 50px;
}
.h1text{
    padding-top: 30px;
    font-size: 67px;
    font-weight: 400;
    padding-left: 165px;
}
</style>