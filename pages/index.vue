<template>
  <div class="container">
    <div>
      <Navbar />
  </div>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';

export default {
  components: {
    Navbar
  }
}
</script>

<style>
/* import Lato regular and bold fonts */
@import url('https://fonts.googleapis.com/css?family=Lato:400,700&display=swap');

:root {
  --button-background: #feb2b2;
  --button-access: #fc8181;
  --button-font: 'Lato', sans-serif;
}
</style>

<style scoped>

</style>
