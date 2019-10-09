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
      return {"slug":"eius-nihil","name":"Qui voluptatem eum natus.","description":"Voluptates distinctio veritatis. Saepe aspernatur aliquam. Voluptates qui enim.","price":76946.23,"header":"Temporibus modi explicabo eum.","footer":"Rerum sed libero eaque.","moreInfo":"Qui aperiam minus repudiandae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
