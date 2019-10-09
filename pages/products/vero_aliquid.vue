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
      return {"slug":"vero_aliquid","name":"Voluptas aut qui quos.","description":"Illum qui qui. Perspiciatis sed non. Rerum nisi nemo.","price":53169.11,"header":"Ea voluptas aliquid exercitationem.","footer":"Aut suscipit molestias beatae.","moreInfo":"Quisquam cumque et est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
