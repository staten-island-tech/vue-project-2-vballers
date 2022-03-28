 <template>
    <!-- <div class="TopBorder">
        <header class="header sticky sticky--top js-header">

  <div class="grid">

    <nav class="navigation">
      <ul class="navigation__list navigation__list--inline">
        <li class="titleHome"><NuxtLink to="/" class="navigation__link navigation__link--is-active">Home</NuxtLink></li>
        <li class="titlePlayers"><NuxtLink to="/players" class="navigation__link">Meet Our Players</NuxtLink></li>
      </ul>
    </nav>

  </div>

</header>
</div>-->





 <div class="header">

   <div class="inner_header">
     <div class="logo_container">
        <a href="https://www.siths.org/" to="/players" class="meow"><h1>MSIT</h1></a>
     </div>

   
     <ul class="navigation">
       <NuxtLink to="/" class="links"><li>Home</li></NuxtLink>
       <NuxtLink to="/players" class="links"><li>Meet Our Players</li></NuxtLink>
       
     </ul>

   </div>
      <img class="logo" src="https://i.imgur.com/x8ZjQJl.png" alt="logo">
   
 </div>
 


  
</template>

<script>


</script>

<style scoped>


.header {
  width: 100%;
  height: 120px;
  display: block;
  background-color: rgba(220, 203, 115, 1);
}

.logo{
  height: 10rem;
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-top: -1rem;

}
.inner_header {
  width: 90%;
  height: 100%;
  display: block;
  margin: 0 auto;
}

.logo_container{ 
  height: 100%;
  display: table;
  float:right;

}

.logo_container h1{ 
  color: white;
  height: 100%;
  display: table-cell;
  vertical-align: middle;
  font-size: 3rem;
  
}

.navigation{
  float: left;
  height:100%;
}

.links {
  height: 100%;
  display: table;
  float: left;
  padding: 0px 20px;
  text-decoration-color:white;
}

.navigation links:last-child{
  padding-right: 0;
}

.navigation li{
  display:table-cell;
  vertical-align: middle;
  height: 100%;
  color: white;
  font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  font-size: 2rem;
}




/* .nav {
  background-color: pink;
  overflow: hidden;

  

}

.links {
  margin-left: 3rem;
  font-size: 3rem;
  padding: 14px 16px;
} */



</style> 

