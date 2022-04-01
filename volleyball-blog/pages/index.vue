<template>
  <div>
    <div><TopBorder></TopBorder></div>
    <div><FrontText></FrontText></div>
    <div><FrontBox></FrontBox></div>
    <div><Footer></Footer></div>
  </div>

  
  

</template>

<script>
import FrontText from '../components/FrontText.vue';
export default {
  components: { FrontText },
  name: 'IndexPage',
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
    };
  },
};

</script>



<style>

 

body
* {
 background-color: #000000;

 position: relative;
} 


html, body,
* {
  font-size: 10px;
  margin: 0;
  padding: 0;
  box-sizing:border-box;
}

.title {
  color: black;
  font-size: 7rem;
  /* font-family: 'Wendy One', sans-serif;  */
  text-align: center;
}

</style>








