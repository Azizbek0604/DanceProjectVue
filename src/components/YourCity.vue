<script>

</script>

<template>
    <div class="container">
        <div class="leftSide">
            <h1 class="leftH">Your city is <br>
            Our city</h1>
            <p class="leftP">Our rides are available in <br> 5 European cities — and <br> counting.</p>
            <button class="btn">StraT now</button>
            <p class="leftP">Want to see Dance in your city?</p>
        </div>

        <div class="rightSide">
            <h1 class="rightH">Berlin</h1>
            <h1 class="rightH">Hambrug</h1>
            <h1 class="rightH">Munich</h1>
            <h1 class="rightH">Paris</h1>
            <h1 class="rightH">Vienna</h1>
        </div>
    </div>
</template>

<style scoped>
.rightH{
    font-size: 108px;
    color: #fff;
}
.container{
    background-image: url('@/images/boymoto.svg');
    min-height: 100vh;
    background-size: cover;
    background-repeat: no-repeat; 
    background-position: center;  
    padding-top: 100px;
    display: flex;
    gap: 400px;
}
.leftH{
    font-size: 65px;
    font-weight: 400;
    color: #fff;
    padding-top: 150px;
}
.leftP{
    font-size: 21px;
    font-weight: 400;
    color: #fff;
    padding-top: 30px;
}
.btn{
    margin-top: 40px;
}
.btn {
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
</style>