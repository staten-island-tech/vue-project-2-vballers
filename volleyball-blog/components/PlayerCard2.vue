<template>
    <div>
        <Nuxt-link to="/joe" class="box">
            <div class="headshotdiv"> <img class="headshot" src="https://www.pinclipart.com/picdir/middle/142-1421318_abdu-sentamu-person-image-placeholder-clipart.png " alt=""></div>
            <div class="container-text player-number">17</div>
            <div class="container-text player-name">Joe Royzman</div>
            <div class="bio">
                <div class=" player-position">Setter / </div>
                <div class=" player-height"> 6'0 / </div>
                <div class=" player-year"> Junior / </div>
                <div class=" player-ht"> Staten Island, NY</div>
            </div>
            
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
    margin-bottom: 3rem;
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
    margin-left: 19%;
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
    left: 31%;
}

.player-position,
.player-height,
.player-year,
.player-ht {
    background-color: transparent;
    font-size: 2rem;
    float: left;
}



a:link { text-decoration: none; }
a:visited { text-decoration: none; }
a:hover { text-decoration: none; }
a:active { text-decoration: none; }
</style>