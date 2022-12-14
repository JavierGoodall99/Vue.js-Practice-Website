<template>
  <nav>
    <NavBarVue></NavBarVue>
    <router-view/>
    <FooterVue></FooterVue>
  </nav>
  <body>

  </body>
</template>

<script>
import NavBarVue from './components/NavBar.vue';
import FooterVue from './components/Footer.vue';
// import ProductsVue from './components/Products.vue';
// import ContactsVue from './components/Contacts.vue';

export default {
  components:{
    NavBarVue,
    FooterVue,
    // ProductsVue,
    // ContactsVue
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  background-color: rgb(0, 0, 0);
}

nav {
  padding: 0px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
