<script >
export default{
    name:"AppHeader"
}
</script>

<template>
<header >
    <div class="container d-flex justify-content-between align-items-center">
        <div class="logo p-4"><img src="/img/dc-logo.png" alt=""></div>
        <div>
            <a href="#">CHARACTERS</a>
            <a href="#" class="hover">COMICS</a>
            <a href="#">MOVIES</a>
            <a href="#">TV</a>
            <a href="#">GAMES</a>
            <a href="#">COLLECTIBLES</a>
            <a href="#">VIDEO</a>
            <a href="#">FANS</a>
            <a href="#">NEWS</a>
            <a href="#">SHOP</a>
        </div>
    </div>
</header>
</template>

<style scoped>
header{
    background-color: white;
    color: black;
    width: 100%;
}
a{
    padding-bottom: 3rem;
    color: black;
    text-decoration: none;
    margin: 1rem;   
    
}
.hover{ 
    border-bottom: 3px solid rgb(35, 35, 255);
    color: rgb(35, 35, 255);;
}
</style>
