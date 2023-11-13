<template>
  <div class="grid-container">
    <div class="menu"></div>
    <div class="main">

    </div>
  </div>
</template>

<script>
  // Add any JavaScript logic here if needed
</script>

<style scoped>
.menu {
  width: 300px;
  background-color: aquamarine;
  justify-content: center;
}

.main {
  justify-content: center;
}
  

.grid-container {
  position: absolute;
  top: 0;
  left: 0;
  width: 100vw; /* Use viewport width to take up the entire width of the page */
  height: 100vh; /* Use viewport height to take up the entire height of the page */
  display: grid;
  grid-template-areas: 'menu main';
}
</style>
