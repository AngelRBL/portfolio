<template>
  <div id="app">
    <Navbar/>
    <router-view/>
    <Footer/>
  </div>
</template>
<script>
import Footer from './components/Footer.vue'
  import Navbar from './components/Navbar'
export default {
  components: {
    Navbar,
    Footer
  }
}
</script>
<style>
@import '../src/assets/css/animate.css';
@import url('https://fonts.googleapis.com/css2?family=Raleway&display=swap');

#app {
  font-family: 'Raleway', sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>
