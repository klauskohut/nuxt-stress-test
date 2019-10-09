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
      return {"slug":"aspernatur_quo","name":"Dolorum aut amet optio.","description":"Distinctio impedit laboriosam. Dolorum quisquam corporis. Qui aut ut.","price":54252.17,"header":"Cupiditate rerum eos est.","footer":"Quas consequatur excepturi in.","moreInfo":"Blanditiis amet temporibus et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
