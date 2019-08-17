<template>
  <router-link to= "/" class="navbar-button" :class="$style">{{ text }}</router-link>
</template>

<script>
export default {
  name: 'NavbarButton',
  props: {
    text: {
      type: String,
      default: ""
    },
    $style: {
      type: String,
      default: ""
    }
  }
}
</script>

<style scoped>

  .navbar-button {
    background-color: var(--button-background);
    color: #fff;
    font-family: var(--button-font);
    font-weight: bold;
    border-radius: 5px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1), 0px 2px 4px rgba(0, 0, 0, 0.06);
    font-size: 1.5vw;
    text-align: center;
    cursor: pointer;

    display: flex;
    align-items: center;
    justify-content: center;
    width: 7.5vw;
    height: 4.5vh;

    transition: background-color 1s;
  }

  .navbar-button:hover {
    background-color: #fc8181;
  }

  .navbar-button.-login {
    background-color: #fff;
    color: var(--button-login);
  }

  .navbar-button.-login:hover {
    background-color: #f2f2f2;
  }

</style>