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
      return {"slug":"modi_dignissimos","name":"Voluptas quaerat est facilis.","description":"Soluta doloremque reprehenderit. Voluptas tempora rerum. Accusamus nisi quasi.","price":91584.82,"header":"Quia odio assumenda necessitatibus.","footer":"Aut et laudantium magnam.","moreInfo":"Sed adipisci occaecati dicta."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
