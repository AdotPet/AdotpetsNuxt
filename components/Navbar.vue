<template>
  <div class="navbar-container">
    <div class="buttons">
      <NavbarButton text="Home" />
      <NavbarButton text="Doar" />
      <NavbarButton text="Adotar" />
      <NavbarButton text="Dicas" />
      <NavbarButton text="Sobre Nós" />
    </div>
    <div class="access-button">
      <NavbarButton text="Acessar" $style="-access" />
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
  height: 80px;
  background-color: #ebf4ff;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.05), 0px 10px 15px rgba(0, 0, 0, 0.1);
}

.navbar-container > .buttons {
  display: flex;
  width: 60%;
  justify-content: space-between;
  align-items: center;
  margin: auto;
}

.navbar-button {
  width: 120px;
  height: 50px;
  line-height: 45px;
  margin-top: 15px;
}

.navbar-button.-access {
  position: absolute;
  right: 45px;
  top: 0;
}
</style>
