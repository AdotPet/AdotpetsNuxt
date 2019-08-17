<template>
  <div class="navbar-container">
    <img :src="Logo" alt="AdotPets Logo" class="logo-icon"/>
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
import Logo from '~/assets/imgs/header/logo.svg';

export default {
  components: {
    Logo,
    NavbarButton
  }
};
</script>script

<style scoped>
.navbar-container {
  width: 100vw;
  height: 7vh;
  background-color: #ebf4ff;

  display: flex;
  align-items: center;
}

.logo-icon {
  position: absolute;
  left: 15px;
}

.navbar-container .buttons {
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
