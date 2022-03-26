<template>
  
<TopBorder></TopBorder>
  <!-- <h1 class="title"> MSIT BOYS VOLLEYBALL </h1> -->
  

</template>

<script>
export default {
  name: 'IndexPage',
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
    };
  },
};

</script>



<style>







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








