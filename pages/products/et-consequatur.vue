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
      return {"slug":"et-consequatur","name":"Eveniet consequatur qui quo.","description":"Minima voluptate dolorem. Harum sunt qui. Iure et dignissimos.","price":36007.74,"header":"Et architecto occaecati voluptas.","footer":"Soluta voluptatem est ducimus.","moreInfo":"In dolores voluptas similique."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
