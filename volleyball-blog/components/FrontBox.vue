<template>
    <div class="container">
        <div class="box2"></div>
        <div class="box">
            <h1>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Eget egestas purus viverra accumsan in nisl nisi scelerisque eu. Gravida dictum fusce ut placerat orci nulla pellentesque dignissim. Quam lacus suspendisse faucibus interdum posuere lorem ipsum dolor sit. Enim nec dui nunc mattis enim ut tellus elementum sagittis. Nulla malesuada pellentesque elit eget gravida. Suspendisse interdum consectetur libero id faucibus. Sit amet mattis vulputate enim nulla. Fringilla ut morbi tincidunt augue interdum. Aliquam ultrices sagittis orci a. Sed arcu non odio euismod lacinia at quis risus sed. Interdum consectetur libero id faucibus nisl tincidunt eget nullam non.

                YES MAAM


            </h1>
        </div>
        
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
          delay: .5,
        })

        tl.from(".box2", {
          x: -500, 
          opacity: 0,
          duration: 2,
         
          }
         )
         tl.from(".box", {
          delay: .1,
          opacity: 0,
          duration: 2,
         
          }
         )
         
         
         }} 
         

}

    
</script>

<style scoped>

.container{
    text-align: center;
    margin-top: 40rem;
    margin-bottom: 0rem;
}
.box{
    border: 10px solid white;
    display: inline-block;
    width: 1250px;
    height: 400px;
    background-color: lightgray;
    bottom: 370px;
}

h1{
    background-color: transparent;
    font-size: 25px;
    

}
.box2{
    border: 10px solid;
    display: inline-block;
    width: 900px;
    height: 600px;
    margin: 10rem;
    background-color: lightgray;
    bottom: 440px;
    background-image: url(https://i.imgur.com/mhhXErr.jpg);
    background-repeat: no-repeat;
    background-size: 100%;
    background-position: center center;
    
}


@media screen and (max-width: 1404px) {
 .box{
   width: 60%;
 }

 .box2{
   width: 50%;
   
 }
  
}

@media screen and (max-width: 1124px) {
 .box{
   width: 60%;
   height: 500px;
 }

 .box2{
   width: 50%;
 }
}
</style>