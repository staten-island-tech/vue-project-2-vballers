 <template>


 <div class="header">

   <div class="inner_header">
     <div class="logo_container">
        <!-- <a href="https://www.siths.org/" class="meow"><h1>MSIT</h1></a> -->
     </div>

   
     <ul class="navigation">
       <NuxtLink to="/" class="links"><li>Home</li></NuxtLink>
       <NuxtLink to="/players" class="links"><li>Meet Our Players</li></NuxtLink>
       
     </ul>
     
        <!-- <a href="https://www.siths.org/"> -->
          <img class="logo" src="https://i.imgur.com/x8ZjQJl.png" alt="logo">
        <!-- </a> -->
     
    

   </div>
     
   
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
  height: 15rem;
  display: block;
  margin-left: auto;
  margin-right: auto;
  background-color: transparent;
  top: -7px;
  right: 120px;

 
}

.inner_header {
  width: 100%;
  height: 100%;
  display: block;
  margin: 0 auto;
  background-color: rgba(220, 203, 115, 1);
}

.logo_container{ 
  height: 100%;
  display: table;
  float:right;
  background-color: rgba(220, 203, 115, 1);
  

}

.logo_container h1{ 
  color: black;
  height: 100%;
  display: table-cell;
  vertical-align: middle;
  font-size: 3rem;
  background-color: rgba(220, 203, 115, 1);
  
  
  
}

.navigation{
  float: left;
  height:100%;
  background-color: rgba(220, 203, 115, 1);
}

.links {
  height: 100%;
  display: table;
  float: left;
  padding: 0px 20px;
  text-decoration-color:black;
  background-color: rgba(220, 203, 115, 1);
  left: 5rem;
}

.navigation links:last-child{
  padding-right: 0;
  background-color: rgba(220, 203, 115, 1);
}

.navigation li{
  display:table-cell;
  vertical-align: middle;
  height: 100%;
  color: black;
  font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  font-size: 2rem;
  background-color: rgba(220, 203, 115, 1);

}

.meow {
  text-decoration: none;
  font-weight: bold;
}


</style> 

