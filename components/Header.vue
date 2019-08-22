<template>
  <div class="header-container">
    <div class="text-container">
      <h1>AdoptPets</h1>
      <h2>Abra seu coração e adote um novo amigo.</h2>
      <router-link to="/" class="match-btn">Encontre um par</router-link>
    </div>
    <div class="image-container"></div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.header-container {
  width: 100%;
  height: 20vw;
  background-color: #9f7aea;

  display: grid;
  grid-template-columns: 1.8fr 1fr;

  position: relative;
}

.text-container {
  width: 100%;
  height: 100%;

  margin-top: -2vw;

  display: flex;
  flex-wrap: nowrap;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.text-container > h1,
.text-container > h2 {
  font-family: var(--button-font);
  font-weight: bold;
  color: #fff;

  text-align: center;
}

.text-container > h1 {
  font-size: 4vw;
}

.text-container > h2 {
  font-size: 2.5vw;
}

.text-container > .match-btn {
  font-family: var(--button-font);
  font-weight: bold;
  font-size: 1.4vw;
  color: #fff;
  background-color: var(--color-pink-darker);
  border-radius: 10px;
  text-align: center;
  line-height: 4vw;

  width: 14vw;
  height: 4vw;

  margin-top: 1vw;
}

.image-container {
  align-items: center;
}
</style>