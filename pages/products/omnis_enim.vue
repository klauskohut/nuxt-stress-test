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
      return {"slug":"omnis_enim","name":"Corporis eos inventore possimus.","description":"Doloribus aut ut. Quia neque atque. Corporis consequuntur voluptatibus.","price":63970.35,"header":"Quae voluptatem voluptas optio.","footer":"Ut totam et sed.","moreInfo":"Ut aspernatur mollitia id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
