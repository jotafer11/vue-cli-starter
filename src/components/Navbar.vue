<template>
<div class="collapse" id="navbarToggleExternalContent">
  <div class="bg-dark p-4">
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
  </div>
</div>
<nav class="navbar navbar-dark bg-dark">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
  </div>
</nav>  
</template>



<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>

a {
  color: #6c757d!important;
}


.bg-dark {
    --bs-bg-opacity: 0;
}


</style>
