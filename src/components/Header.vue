<template>
  <div class="container-fluid">
  <div class="nav">

    <!--img img alt="Art logo" src="../assets/icon_paintbrush.png" class="logo__img" /-->
    <span style="font-family: Helvetica,sans-serif ">
    <a href="#">Social Art Network, Welcome ! </a>
    <a href="#">Home</a>
    <a href="#"><SearchBar /></a>
    <a href="#">Profile</a>
    <a href="#">Logout</a>
    </span>
  </div>
  </div>
</template>

<script>

import SearchBar from "./SearchBar";

export default {
  name: "Header",
  components: {
    SearchBar
  }
}
</script>

<style scoped>
.nav {
  background-color: #ffffff;
  border-radius: 30px;
  position: fixed;
  top: 0;
  left: 0;
  height: 4rem;
  z-index: 1;
  width: 100%;
}
.nav a {
  float: left;
  color: #6ee16e;
  border-radius: 30px;
  padding: 20px 65px;
  text-align: center;
  front-size: 30px;
  height: 4rem;
  text-decoration: none;
  margin-right: 5px;
}

.nav a:hover{
  background: #a2fa9f;
  border-radius: 30px;

  color:#2c3e50;
}

.logo__img {
  width: 100%;
  height: 100%;
}
img {
  size: 12px;
}


</style>