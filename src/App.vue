
<template>
    <div class="main"></div>
    <div class="weather-img">
        <img src="/wind.png" width="80px" height="auto" alt="wind"/>
    </div>
</template>

<style scoped>
    .main {
        width: 100%;
        height: 100vh;
        position: absolute;
        z-index: -10;
        background: linear-gradient(102deg, rgba(249,255,207,1) 0%, rgba(136,255,209,1) 50%, rgba(41,205,255,1) 100%);
        filter: blur(12px);
    }
    .weather-img {
        position: relative;
        z-index: 10;
        width: 300px;
        height: 400px;
        border-radius: 15px;
        box-shadow: 0px 0px 5px rgb(98, 100, 92);
        transition: .3s;
    }
    .weather-img:hover {
        box-shadow: 0px 0px 25px rgb(98, 100, 92);
        cursor: pointer;
    }
</style>