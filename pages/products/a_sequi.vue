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
      return {"slug":"a_sequi","name":"Omnis quidem laborum in.","description":"Atque qui quos. Qui commodi rem. Saepe modi voluptates.","price":56185.11,"header":"At nisi dolores necessitatibus.","footer":"Qui amet id tempore.","moreInfo":"Aut amet sint quo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
