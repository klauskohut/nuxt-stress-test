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
      return {"slug":"porro-doloribus","name":"Impedit quia modi aliquid.","description":"Atque reprehenderit quisquam. Odio reiciendis quam. Voluptatem ullam voluptatem.","price":67745.83,"header":"Iure quisquam accusantium quia.","footer":"Et quis sit ab.","moreInfo":"Libero voluptas aut qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
