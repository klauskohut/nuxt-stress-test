<template>
  <section>
    <Header :message="header" />
    <div class="container">
      <h1>{{ name }}</h1>
      <h2>{{ slug }}</h2>
      <p>{{ description }}</p>
      <strong>{{ price }}</strong>
    </div>
    <div class="container">
      <slot />
    </div>
    <Footer :message="footer" />
  </section>
</template>

<script>
  import Header from '../components/Header'
  import Footer from '../components/Footer'
  export default {
    props: ['header', 'footer', 'name', 'slug', 'description', 'price'],
    components: {
      Header,
      Footer
    }
  }
</script>

<style>
  .container {
    padding: 1em;
    height: inherit;
    width: inherit;
  }
</style>
