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
      return {"slug":"nihil_quisquam","name":"Sed quas qui rerum.","description":"Molestiae doloremque eius. Sint omnis impedit. Voluptate minima totam.","price":93788.04,"header":"Doloremque ut asperiores aperiam.","footer":"Voluptatem facere quidem perspiciatis.","moreInfo":"Suscipit possimus deleniti sequi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
