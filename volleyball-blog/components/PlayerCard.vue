<template>
    <div>
        <Nuxt-link to="/enoch" class="box">
            <div class="headshotdiv"> <img class="headshot" src="https://www.pinclipart.com/picdir/middle/142-1421318_abdu-sentamu-person-image-placeholder-clipart.png " alt=""></div>
            <div class="container-text player-number">19</div>
            <div class="container-text player-name">Enoch Chan</div>
            <div class="bio player-position">Outside / </div>
            <div class="bio player-height"> 6'1 / </div>
            <div class="bio player-year"> Senior / </div>
            <div class="bio player-ht"> Staten Island, NY</div>
        </Nuxt-link>

    </div>
</template>

<script>
    
</script>

<style scoped>

.box{
    border: 10px solid white;
    display: block;
    width: 60%;
    height: 20rem;
    background-color: lightgray;
    border-radius: 5rem;
    margin: auto;
    margin-top: 4rem;
}


.headshotdiv {
    background-color: transparent;
    margin-top: 3rem;
    margin-left: 3rem;
    right: 2rem;
}

/* .box {
    opacity: .8;
} */

.headshot {
    width: 12%;
    height: 12%;
    margin-left: 5%;
    border-radius: 50%;
    background-color: transparent;
}


.player-name{
    margin-left: 1%;
    background-color: transparent;
}

.player-number{
    margin-left: 20%;
    vertical-align: middle;
    background-color: rgba(220, 203, 115, 1);
    color: black;
    font-weight: bold;
    padding: 0 8px;
    font-style: italic;
    
}



.container-text {
    font-size: 3rem;
    
    bottom: 50%;
    
    text-decoration: black;
    color: black;
    float: left;

}

.bio{
    background-color: transparent;
    color: black;
    font-size: 2rem;
    float: left;
    bottom: 44%;
    left: 30%;
}





a:link { text-decoration: none; }
a:visited { text-decoration: none; }
a:hover { text-decoration: none; }
a:active { text-decoration: none; }
</style>