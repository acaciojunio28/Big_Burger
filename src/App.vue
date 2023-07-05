<template>
<div>
  <navbar-vue :logo="logo_src" :alt="app_name"/>
  <router-view/>
  <footer-vue/>
  </div>
</template>
<script>
import footerVue from './components/footer.vue'
import navbarVue from './components/navbar.vue'

export default {
  data: function() {
    return {
      logo_src: "/img/logo.png",
      app_name: "Make Your Burger"
    }
  },
   components: {
    navbarVue,
    footerVue
  }
}
</script>
<style>
  * {
    font-family: Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
  .main-container {
    margin: 50px;
    min-height: 250px;
  }
  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }
</style>
