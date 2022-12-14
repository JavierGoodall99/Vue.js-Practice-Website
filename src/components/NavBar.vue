<template>
<nav class="navbar navbar-expand-lg">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
      <img src="https://i.postimg.cc/s25CPvVZ/Digital-Art-Logo.png" alt="Logo" width="70" height="70">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
            <router-link to="/">Home</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/about">About</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/products">Products</router-link>
        </li>
        <li class="nav-item">
            <router-link to="/Contacts">Contact</router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {
    
}
</script>

<!-- CSS -->
<style scoped>

.navbar {
    padding: 0px;

}
   .navbar-nav {
    margin: auto;
   } 

   .nav-item {
    padding: 20px;
   }

  nav a {
    color: white;
    font-family: 'Josefin Slab', serif;
  }

   nav a.router-link-exact-active {
  color: #9434ae;
  font-size: larger;
}


</style>