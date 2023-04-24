<template>
  <Navbar :logo="logo_src" :alt="app_name"/>
  <router-view/>
  <Footer/>
</template>

<script>
import Footer from './components/Footer.vue';
import Navbar from './components/Navbar.vue';
export default {
  components: {
    Navbar,
    Footer
},
data() {
  return {
    logo_src: "/img/logopng",
    app_name: "Make Your Burger"
  }
}
  
}
</script>

<style>

</style>
