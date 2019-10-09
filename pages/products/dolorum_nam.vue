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
      return {"slug":"dolorum_nam","name":"Ratione sed quia illo.","description":"Deserunt quis iusto. Aut minima fugiat. Deserunt et error.","price":88950.52,"header":"Saepe in iste vel.","footer":"Expedita odit eaque molestiae.","moreInfo":"Dolores minus nihil assumenda."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
