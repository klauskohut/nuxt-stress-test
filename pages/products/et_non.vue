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
      return {"slug":"et_non","name":"Corrupti et id sit.","description":"Sapiente qui praesentium. Neque reprehenderit praesentium. Autem sint dolorem.","price":87337.71,"header":"Qui nihil impedit eum.","footer":"Occaecati magnam dolore iure.","moreInfo":"Voluptatem corrupti et sed."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
