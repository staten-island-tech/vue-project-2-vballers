<template>
    <div class="footer golden">
      <div>
        
      </div>

      <div class="seagulls  links cat">
        <li class="Title1">SEAGULLS</li>
        <li class="txt">we stay winning</li>
        <li class="txt">Fear the Flock</li>
      </div>



      <div class="explore cat links">
        <div class="navigation">
        <li class="Title2">EXPLORE</li>
        <NuxtLink to="/" class="txt"><li>Home</li></NuxtLink>
        <NuxtLink to="/players" class="txt"><li>Meet Our Players</li></NuxtLink>
        </div>
      </div>
        

      
        
      <div class="visit links cat">
        <li class="Title2">VISIT</li>
        <a href="https://www.instagram.com/therock/?hl=en" ><li class="txt" id="ig">485 Clawson St, Staten Island, NY 10306</li></a>
      </div>



      <div class="follow links cat">
        <li class="Title2">FOLLOW</li>
        <a href="https://www.instagram.com/therock/?hl=en" ><li class="txt" id="ig">Instagram</li></a>
        <a href="https://www.instagram.com/therock/?hl=en" ><li class="txt" id="ig">Twitter</li></a>
        <a href="https://www.psal.org/profiles/team-profile.aspx#016/31511" ><li class="txt" id="ig">PSAL</li></a>
      </div>

      <div class="legal cat"></div>
      


       


    </div>
</template>

<script>
    
</script>

<style scoped>

.golden{
  background-color: rgba(220, 203, 115, 1);
  z-index: 2;
}

.Title1  {
  
  background-color: rgba(220, 203, 115, 1);
  text-decoration: none;
  list-style-type: none;
  color: black;
  font-size: 30px;
}

.Title2  {
  
  background-color: rgba(220, 203, 115, 1);
  text-decoration: none;
  list-style-type: none;
  color: black;
  font-size: 25px;
}


.footer {
    width: 100%;
    height: 190px;
    display: block;
    background-color: rgba(220, 203, 115, 1);
    margin-bottom: 0px;
    position: absolute;
    left: 0;
    bottom: 0;
    background-image: none;
    
}

.cat {
  float: left;
  margin-left: 16%;
  text-align: center;
  margin-top: 6rem;
  right: 4.5%;
  background-color: rgba(220, 203, 115, 1);

}

.visit {
  width: 13rem;
  background-color: rgba(220, 203, 115, 1);
}

.links {
  margin-top: 6rem;
}
.links li {
  background-color: rgba(220, 203, 115, 1);
  text-decoration: none;
  list-style-type: none;
  color: black;
  
}

.txt li{
  font-size: 17px;
  background-color: rgba(220, 203, 115, 1);
}

.txt {
  font-size: 17px;
  background-color: rgba(220, 203, 115, 1);
}


a:link {
  text-decoration: none;  
  background-color: rgba(220, 203, 115, 1);
}


@media screen and (max-width: 1410px) {
 .links{
   margin-left: 12%;
 }
  
}

@media screen and (max-width: 976px) {
 .links{
   margin-left: 7%;
 }

 .seagulls{
   margin-left: 15%;
 }
}

</style>
