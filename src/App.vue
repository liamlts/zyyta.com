<template>
<nav-bar></nav-bar>
  <router-view/>
<zyyta-footer></zyyta-footer>
</template>

<script> 
import NavBar from './components/NavBar/NavBar.vue';
import ZyytaFooter from './components/ZyytaFooter/ZyytaFooter.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    ZyytaFooter
  },
  mounted() {
    document.title = "Zyyta.com | Games and Mods"
  },
  data() {
    return {

    }
  }
}
</script>

<style>
@font-face {
  font-family: "Orbitron";
  src: local("Orbitron"),
  url("./assets/fonts/orbitron/Orbitron-Regular.ttf") format("truetype");
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
