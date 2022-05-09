<template>
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/grid">Grid</router-link> 
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
</template>


<style>

#app {
    background-color: #313146;
    min-height: 100vh;

    text-align: center; 
}



/*    HEADER  **/

#nav {
  padding: 30px;
  color: #dddee0;
}

#nav a {
  font-weight: bold;
  color: #dddee0;
  text-decoration: none;
  margin-left: 20px;
  margin-right: 20px; 
}

#nav a:hover {
  color: #38ef7d;
}



/*    CONTENT **/

#contenedor {
  width: 90%;
  max-width: 800px;
  margin: auto;
  border: 2px solid #767684;
  color: #767684;
  border-radius: 20px;
  padding: 25px 50px 75px;
  min-height: 400px;
}

</style>
