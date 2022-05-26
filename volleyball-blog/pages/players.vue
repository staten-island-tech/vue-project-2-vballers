<template>
    <div>
        <div><TopBorder></TopBorder></div> 
        <div class="player enoch"><PlayerCard></PlayerCard></div> 
        <div class="player pat"><PlayerCard6></PlayerCard6></div>
        <div class="player aidan"><PlayerCard4></PlayerCard4></div>
        <div class="player gunhee"><PlayerCard8></PlayerCard8></div>
        <div class="player joe"><PlayerCard2></PlayerCard2></div>
        <div class="player donny"><PlayerCard3></PlayerCard3></div>
        <div class="player heo"><PlayerCard5></PlayerCard5></div>
        <div class="player lastCard roni"><PlayerCard7></PlayerCard7></div>
        
        <div><Footer></Footer></div>

    </div>
</template>

<script>
export default {
     mounted(){
        this.animateOnScroll()
    },

    methods: {
      animateOnScroll() {
        const tl = this.$gsap.timeline({
          delay: 1,
        })

        tlh.from(".player", {
          /* x: -250, */
          opacity: 0,
          duration: .75,
          stagger: .3,
          /* ease: 'Power1.easeInOut', */ 
          }
         )
         }} 
}
    
</script>

<style scoped>
body
* {
 background-color: black;
 height: 200%;
 position: relative;
} 

h1{
  height:100rem;
}
html, body,
* {
  font-size: 10px;
  margin: 0;
  padding: 0;
  box-sizing:border-box;
}

html
* {
  background-color: transparent;
  /* background-image: url("https://i.imgur.com/26Ht5k3.png") ; */
  background-color: black;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  background-attachment: fixed;
} 

.lastCard{
  margin-bottom: 19rem;
}

 /* https://i.imgur.com/26Ht5k3.png
 https://imgur.com/8adMbw2.png */

</style>