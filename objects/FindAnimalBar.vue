<template>
  <nav class="menu">
    <router-link to='/' class="menu-cel -first">Qual seu Animal Favorito?</router-link>
    <router-link to='/' class="menu-cel -second">Encontre um cão</router-link>
    <router-link to='/' class="menu-cel third">Encontre um gato</router-link>
  </nav>
</template>
<script>
export default {
  
}
</script>
<style scoped>
  .menu {
    width: 45vw;
    height: 8vh;
    margin: auto;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    text-align: center;
    background-color: var(--color-pink);
    border-radius: 8px;
    
    color: #fff;
    font-family: var(--button-font);
    font-weight: bold;
    font-size: 1.1vw;
  }

  .menu-cel {
    margin: auto;
  }

</style>