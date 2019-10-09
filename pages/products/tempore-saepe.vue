<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <Slider />
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  import Slider from '../../components/Slider'

  export default {
    layout: 'product',
    components: {
      Product,
      Slider
    },
    data() {
      return {"slug":"tempore-saepe","name":"Vel vel dicta incidunt.","description":"Non deleniti eos. Voluptate saepe cum. Culpa ducimus vitae.","price":12489.66,"header":"Temporibus molestiae id neque.","footer":"Quo debitis praesentium vitae.","moreInfo":"Qui amet similique reprehenderit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
