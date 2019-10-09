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
      return {"slug":"enim_laborum","name":"Ipsum qui a impedit.","description":"Consequatur rerum corrupti. Optio officia quis. Temporibus et veritatis.","price":64909.56,"header":"Voluptatem numquam blanditiis asperiores.","footer":"Enim ut esse iusto.","moreInfo":"Quidem minus quia necessitatibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
