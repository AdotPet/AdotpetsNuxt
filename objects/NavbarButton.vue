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
    text-align: center;
    border-radius: 5px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1), 0px 2px 4px rgba(0, 0, 0, 0.06);
    font-size: 18px; 
    text-shadow: 0px 4px 6px rgba(0, 0, 0, 0.05), 0px 10px 15px rgba(0, 0, 0, 0.1);
  }

  .navbar-button.-access {
    background-color: #fff;
    color: var(--button-access);
  }

</style>