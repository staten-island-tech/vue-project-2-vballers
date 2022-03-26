 <template>
    <div class="TopBorder">
        <header class="header sticky sticky--top js-header">

  <div class="grid">

    <nav class="navigation">
      <ul class="navigation__list navigation__list--inline">
        <li class="titleHome"><a href="/pages/index.vue" class="navigation__link navigation__link--is-active">Home</a></li>
        <li class="titlePlayers"><a href="/pages/players.vue" class="navigation__link">Meet Our Players</a></li>
      </ul>
    </nav>

  </div>

</header>


        
        
        <!-- <a href="secret" class="titleHome">Home</a>
        <a href="Players" class="titlePlayers">Meet Our Players</a> -->

        
    </div>
</template>

<script>
    
</script>

<style scoped>

/* .titleHome,.titlePlayers {
color:green;
text-align: left;
margin: 4rem;
font-size: 3rem;
text-decoration: none;
margin-top: 2rem;
    
}
 */
/* helpers/grid.css */

.grid {
  inline-size: 90%;
  margin-inline: auto;
  max-inline-size: 48em;
}

/* helpers/sticky.css */

.sticky {
  position: sticky;
  will-change: transform;
}

.sticky--top {
  top: 0;
}

/* layout/base.css */

* {
  box-sizing: inherit;
}

html {
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  line-height: 1.75;
  margin: 0;
  min-block-size: 100vh;
}

/* layout/header.css */

.header {
  background-color: #fff;
  padding-block: 1em;
}


.header::after {
  bottom: 0;
  box-shadow: 0 0.0625em 0.5em rgba(0, 0, 0, 0.3);
  content: '';
  left: 0;
  opacity: 0;
  position: absolute;
  right: 0;
  top: 0;
  transition: opacity 0.3s;
  z-index: -1;
}

.header.is-active::after {
  opacity: 1;
}

/* layout/main.css */

.main {
  padding-block: 6em;
}

/* modules/headline.css */

h1 {
  margin-block: 0 0.5em;
}

/* modules/navigation.css */

.navigation__list {
  list-style: none;
  margin: 0;
  padding: 0;
}

.navigation__list--inline {
  display: flex;
  gap: 1.5em;
}

.navigation__link {
  color: inherit;
  display: block;
  padding-inline: 1em;
  text-decoration: none;
}

.navigation__link--is-active {
  background-color: #000;
  border-radius: 999em;
  color: #fff;
}

/* modules/paragraph.css */

p {
  padding-block: 1.5em;
}

</style> 

