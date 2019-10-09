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
      return {"slug":"voluptas-recusandae","name":"Laboriosam labore consequatur iusto.","description":"Cumque et voluptate. Reprehenderit asperiores aut. Alias et ut.","price":62923.14,"header":"Recusandae a ut earum.","footer":"Dignissimos recusandae maxime sunt.","moreInfo":"Aliquid voluptas in incidunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
