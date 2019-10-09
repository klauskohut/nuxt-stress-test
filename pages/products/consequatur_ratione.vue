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
      return {"slug":"consequatur_ratione","name":"Ut quaerat dicta temporibus.","description":"Quae reiciendis laborum. Consequatur qui et. Ab architecto unde.","price":32796.83,"header":"Ducimus aliquam aut facere.","footer":"Eos animi dolores quod.","moreInfo":"Nihil dolores quia consequuntur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
