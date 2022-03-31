<template>
    <div class="footer">
        <ul class="navigation">
        <NuxtLink to="/" class="links"><li>Home</li></NuxtLink>
        <NuxtLink to="/players" class="links"><li>Meet Our Players</li></NuxtLink>
       
        </ul>

    </div>
</template>

<script>
    
</script>

<style scoped>


.footer {
    width: 100%;
    height: 120px;
    display: block;
    background-color: rgba(220, 203, 115, 1);
    margin-bottom: 0px;
    position: absolute;
    left: 0;
    bottom: 0;
    
}

.navigation{
  float: left;
  height:100%;
  background-color: rgba(220, 203, 115, 1);
}

.links {
  height: 100%;

  padding: 0px 20px;

  background-color: rgba(220, 203, 115, 1);
}



</style>
