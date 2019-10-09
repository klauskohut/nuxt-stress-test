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
      return {"slug":"sunt-repellendus","name":"Quas optio unde est.","description":"Molestias quo sed. Sapiente eveniet occaecati. Quibusdam ipsa qui.","price":29929.35,"header":"Dolorem vel omnis commodi.","footer":"Aliquam ducimus numquam iste.","moreInfo":"Repudiandae quo qui dolores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
