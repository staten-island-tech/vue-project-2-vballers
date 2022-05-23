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
        this.$gsap.from(window, {duration: 2, scrollTo: 1000})

        this.$gsap.from(".title", {
          x: 500,
          ease: 'Power1.easeInOut',
          scrollTrigger: {
            trigger: '.content',
            pin: true,
            end: 'bottom',
            scrub: true
          }
        } )

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