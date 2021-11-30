<template>
  <div>
    <div>
      <Navbar />
    </div>
    <router-view />
    <div>
      <Footer />
    </div>
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";

export default {
   data: function() {
    return {
      logo_src: "/img/logo.png",
      app_name: "Make Your Burger"
    }
  },
  components: {
    Navbar,
    Footer,
  },
};
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
