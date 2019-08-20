<template>
  <div class="container">
      <Navbar />
      <FindAnimalBar />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';
import FindAnimalBar from '~/objects/FindAnimalBar.vue';

export default {
  components: {
    Navbar,
    FindAnimalBar
  }
}
</script>

<style>
/* import Lato regular and bold fonts */
@import url('https://fonts.googleapis.com/css?family=Lato:400,700&display=swap');

:root {
  --color-pink-lighter: #feb2b2;
  --color-pink-darker: #f56565;
  --color-pink: #fc8181;

  --button-font: 'Lato', sans-serif;
}
</style>

<style>
  .container {
    max-width: 100vw;
  }

</style>
