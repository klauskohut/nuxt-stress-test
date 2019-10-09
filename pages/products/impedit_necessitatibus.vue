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
      return {"slug":"impedit_necessitatibus","name":"Nostrum in qui ab.","description":"In doloremque et. Omnis omnis sequi. Reiciendis omnis repellendus.","price":14204.13,"header":"Ducimus necessitatibus accusamus expedita.","footer":"Rerum enim in vitae.","moreInfo":"Recusandae est dolor quibusdam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
