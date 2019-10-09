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
      return {"slug":"impedit-ipsum","name":"Iure quaerat dicta sit.","description":"Odit et eaque. Quo cupiditate rerum. Et excepturi saepe.","price":44769.78,"header":"Dolorum soluta reiciendis impedit.","footer":"Consequatur et sed aut.","moreInfo":"Dolorem aliquid animi aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
