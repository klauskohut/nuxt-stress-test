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
      return {"slug":"mollitia_et","name":"Qui rerum neque omnis.","description":"Sit voluptates excepturi. Ex aperiam repudiandae. Sed iusto et.","price":72668.96,"header":"Sunt impedit ab recusandae.","footer":"Iure et consequatur velit.","moreInfo":"Dignissimos debitis eos et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
