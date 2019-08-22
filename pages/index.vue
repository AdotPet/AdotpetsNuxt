<template>
  <div class="container">
      <Navbar />
      <FindAnimalBar />
      <Header />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';
import Header from '~/components/Header.vue';
import FindAnimalBar from '~/components/FindAnimalBar.vue';

export default {
  components: {
    Navbar,
    FindAnimalBar,
    Header
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

.container {
  max-width: 1980px;
  margin: auto;
}
</style>
