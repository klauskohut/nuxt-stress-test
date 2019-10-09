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
      return {"slug":"non-beatae","name":"Similique placeat eos mollitia.","description":"Numquam non laborum. Odio sequi quia. Ut aut accusantium.","price":29714.36,"header":"Aut cupiditate aut illum.","footer":"Eum inventore reprehenderit nemo.","moreInfo":"Consectetur consequatur voluptatem quod."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
