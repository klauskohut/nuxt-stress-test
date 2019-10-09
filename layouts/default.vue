<template>
  <div class="container">
    <nuxt />
  </div>
</template>


<style>
  .container {
    height: 100vh;
    width: 100vw;
    background-color: peachpuff;
  }
  @media (min-width: 800px) {
    .container {
      padding: 1em 4em;
      background-color: papayawhip;
    }
  }

  @media (min-width: 1200px) {
    .container {
      padding: 1em 4em;
      background-color: palegoldenrod;
    }
  }
</style>
