<template>
  <div id="nav">
    <router-link to="/" id="logo-url">
      <img src="/logo.png" alt="logo de hamburguer" id="logo" />
    </router-link>
    <router-link to="/"> Home </router-link>
    <router-link to="/pedidos"> Pedidos </router-link>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>
<style scoped>
#nav {
  background-color: #222;
  border-bottom: 7px solid #000;
  padding: 15px 50px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  font-size: 18px;
}

#nav #logo-url {
  margin: auto;
  margin-left: 0;
}

#logo {
  width: 40px;
  height: 40px;
}

#nav a {
  color: #fcba03;
  text-decoration: none;
  margin: 15px;
  transition: 0.5s;
}

#nav a:hover {
  color: #fff;
}
</style>
