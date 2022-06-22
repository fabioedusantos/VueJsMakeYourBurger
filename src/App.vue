<template>
  <NavBar :logo="logoSrc" :alt="appName"/>
  <router-view/>
  <Footer/>
</template>

<style>
</style>
<script>
import NavBar from "@/components/NavBar";
import Footer from "@/components/Footer";

export default {
  components: {
    Footer,
    NavBar
  },
  data() {
    return {
      logoSrc: '/img/logo.png',
      appName: 'Make Your Burger'
    }
  }
}
</script>

<style>
*{
  font-family: "Helvetica";
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
.main-container{
  margin: 50px;
  min-height: calc(100vh - 278px);
}
h1{
  text-align: center;
  font-size: 42px;
  margin-bottom: 30px;
  color: #222;
}
</style>