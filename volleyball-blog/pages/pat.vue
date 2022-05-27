<template>
  <div>
    <div><TopBorder></TopBorder></div>
    <div class="box">
            <div class="pic"></div>
            <div class="box2"><img class="headshot" src="https://www.pinclipart.com/picdir/middle/142-1421318_abdu-sentamu-person-image-placeholder-clipart.png " alt=""></div>
            <div class="name-container"><h1 class="name">Pat Chen</h1></div>
            <h2 class="bio">Libero / 5'8 / Senior / Staten Island, NY</h2>
            <h2 class="desc">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Eget egestas purus viverra accumsan in nisl nisi scelerisque eu. Gravida dictum fusce ut placerat orci nulla pellentesque dignissim. Quam lacus suspendisse faucibus interdum posuere lorem ipsum dolor sit. Enim nec dui nunc mattis enim ut tellus elementum sagittis. Nulla malesuada pellentesque elit eget gravida. Suspendisse interdum consectetur libero id faucibus. Sit amet mattis vulputate enim nulla. Fringilla ut morbi tincidunt augue interdum. Aliquam ultrices sagittis orci a. Sed arcu non odio euismod lacinia at quis risus sed. Interdum consectetur libero id faucibus nisl tincidunt eget nullam non.
            </h2>
        </div>

 
    <div><FrontText></FrontText></div>
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
        const tlh = this.$gsap.timeline({
          delay: .4,
        })

        tlh.from(".box", {
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

.name-container{
    background-color:rgba(220, 203, 115, 1);
    width: 1230px;
    height: 70px;
    bottom: 320px;
    z-index: 1;
    opacity: 60%;
    margin-bottom: -7rem;
    
}

.name {
    background-color: transparent;
    font-size: 5rem;
    margin-left: 25%;
    margin-top: auto;
    margin-bottom: auto;
}

.box{
    border: 10px solid white;
    width: 1250px;
    height: 950px;
    background-color: white;
    margin-left: auto;
    margin-right: auto;
    margin-top: 10rem;
    margin-bottom: 200px;
    bottom: 10px;
}
 .pic{
     width: 1230px;
     height: 480px;
     background-color: gray;
     background-image: url(https://i.imgur.com/8DXruMR.jpg);
    background-repeat: no-repeat;
    background-size: 100%;
    background-position: center 40%;
     left: 0px;
 }

 .bio{
     background-color: transparent;
     bottom: 220px;
     /* left: 400px; */
     font-size: 3.5rem;
     margin-left: 25%;

 }


.desc{
    background-color: transparent;
    font-size: 2rem;
    line-height: 2;
    bottom: 180px;
}
.box2{
    border: 10px solid rgba(220, 203, 115, 1);
    width: 250px;
    height: 250px;
    background-color: white;   
    z-index: 0;
    top: -150px;
    left: 30px;
    z-index: 2;
}

.box3{
    border: 10px solid white;
    width: 1250px;
    height: 500px;
    background-color: lightgray;
    margin-left: auto;
    margin-right: auto;
    margin-top: 5rem;
    margin-bottom: 200px;
    bottom: 70px;
}


.headshot {
    width: 90%;
    height: 90%;
    margin-left: 5%;
    border-radius: 50%;
    background-color: transparent;
    z-index: 2;
}



</style>








