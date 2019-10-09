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
      return {"slug":"aut-provident","name":"Repellat beatae sit aut.","description":"Harum occaecati saepe. Rerum et quia. Nam dolorem tempora.","price":87749.39,"header":"Eligendi eum dolores quo.","footer":"Ut sed laborum voluptas.","moreInfo":"Doloribus tempora dolor aliquid."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
