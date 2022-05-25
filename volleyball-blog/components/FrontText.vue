<template>
    <div class="content">
        <h1 class="title">MSIT BOYS VOLLEYBALL</h1>
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
          delay: 0.3,
        })

        tl.from(".title", {
          /* x: -250, */
          opacity: 0,
          duration: 0.3,
          stagger: 0.5,
          
          /* ease: 'Power1.easeInOut', */
          }
         )

      }
      }
      
      
      
      }

    
 
</script>

<style scoped>

.title {
    color:white;
    margin-top: 3rem;
    font-weight: bold;
}
</style>