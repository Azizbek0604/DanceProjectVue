<script>
import Logo from '@/images/Logo.svg'


export default {
    data() {
        return{
            Logo
        }
    }
}
</script>

<template>
    <div class="container">
        <div class="navbar">
            <div class="logo">
                <img :src="Logo" alt="Logo">
            </div>
            
            <div  class="links">
                <ul>
                    <li><a href="#">Concierge</a></li>
                    <li><a href="#">Rides</a></li>
                    <li><a href="#">For Business</a></li>
                    <li><a href="#">En</a></li>
                </ul>
                <button class="btn">Start Now</button>
            </div>
        </div>

        <div class="main">
            <h1 class="text">Your future <br>
                is electric
            </h1>
            <p class="parag">
                Get your own ebike or emoped <br>
                with our flexible subscription
            </p>

            <button class="btnn">Start now</button>
        </div>
    </div>
</template>

<style scoped>
.parag{
    padding-top: 50px;
    font-weight: 400;
    font-size: 21px;
    color: #fff;
}
.main{
    text-align: center;
    padding-top: 100px;
}
.text{
    color: #fff;
    font-weight: 400;
    font-size: 120px;
}
.container {
    background: #9A63BE;
    min-height: 100vh; 
}

.navbar {
    display: flex;
    justify-content: space-between; 
    align-items: center; 
    padding-top: 10px;
}
.logo{
    margin-right: 700px;
}
ul {
    list-style: none;
    display: flex;
    gap: 50px; 
}
.links {
    display: flex;
    align-items: center;
}
.logo img {
    height: 65px;
}
a{
    text-decoration: none;
    color: #fff;
    cursor: pointer;
    font-size: 18px;
    font-weight: 400;
    transition: transform 0.6s ease, color 0.6s ease;
    position: relative;
}
a:hover{
    color: gold;
    transform: scale(1.1);
    z-index: 1;
}
a::after {
    content: ''; 
    position: absolute;
    left: 0;
    right: 0;
    bottom: -5px;
    height: 2px; 
    background: gold; 
    transform: scaleX(0); 
    transition: transform 0.3s ease; 
}

a:hover::after {
    transform: scaleX(1); 
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

.btnn {
    margin-top: 50px    ;
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

.btnn:hover {
    transform: scale(1.1); 
    background: #5a30c7; 
    color: gold;
}


</style>
