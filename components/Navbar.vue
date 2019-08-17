<template>
  <div class="navbar-container">
    <div class="buttons">
      <NavbarButton text="Home" />
      <NavbarButton text="Doar" />
      <NavbarButton text="Adotar" />
      <NavbarButton text="Dicas" />
      <NavbarButton text="Sobre Nós" />
      <NavbarButton text="Acessar" $style="-login" />
    </div>
  </div>
</template>

<script>
import NavbarButton from "~/objects/NavbarButton.vue";

export default {
  components: {
    NavbarButton
  }
};
</script>script

<style scoped>
.navbar-container {
  width: 100vw;
  height: 7vh;
  background-color: #ebf4ff;
}

.navbar-container .buttons {
  /* background-color: #fff; */
  height: 100%;
  width: 70%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: auto;
}

.navbar-container .buttons .navbar-button {
  margin-right: 10px;
}

.navbar-container .buttons .navbar-button.-login {
  position: absolute;  
  right: 5px;
}

</style>
