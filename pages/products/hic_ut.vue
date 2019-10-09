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
      return {"slug":"hic_ut","name":"Eum officiis blanditiis porro.","description":"Adipisci quia dignissimos. Porro suscipit repellendus. Numquam non nulla.","price":44968.01,"header":"Quis earum quibusdam dolore.","footer":"Aut minima et corporis.","moreInfo":"Earum odio et adipisci."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
