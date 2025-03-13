
<template>
    <div class="main"></div>
    <div class="weather-img">
        <img src="/winter.png" width="120px" height="auto"/>
    </div>
</template>

<style scoped>
    .main {
        width: 100%;
        height: 100vh;
        position: absolute;
        z-index: -10;
        background-image: url("/fon.avif");
        background-repeat: no-repeat;
        background-size: cover;
        filter: blur(12px);
    }
    .weather-img {
        position: relative;
        z-index: 10;
        width: 300px;
        height: 400px;
        border-radius: 15px;
        box-shadow: 0px 0px 5px rgb(78, 78, 244);
        transition: .3s;
    }
    .weather-img:hover {
        box-shadow: 0px 0px 25px rgb(78, 78, 244);
        cursor: pointer;
    }
</style>