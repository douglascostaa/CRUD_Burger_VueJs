<template>
  <div id="main-banner">
    <h1>Burguer do Gaiteiro</h1>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
#main-banner {
  background-image: url("/burger.jpg");
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  height: 400px;
  display: flex;
  justify-content: flex-start;
  align-items: center;
}

#main-banner h1 {
  color: #fff;
  background-color: #222;
  padding: 15px;
  border-radius: 0 30px 30px 0;
}
</style>
