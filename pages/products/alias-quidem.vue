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
      return {"slug":"alias-quidem","name":"Quia quia adipisci sit.","description":"Minus dignissimos et. Omnis atque tempore. Et omnis est.","price":29680.67,"header":"Ullam magni sint voluptas.","footer":"Veritatis ut et aut.","moreInfo":"Repellat aut et illum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
