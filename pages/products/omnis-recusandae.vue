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
      return {"slug":"omnis-recusandae","name":"Ad autem a adipisci.","description":"Et dolorem fugiat. Accusantium inventore vel. Itaque expedita vel.","price":64050.32,"header":"Quasi odit tenetur aut.","footer":"Itaque commodi debitis quod.","moreInfo":"Qui veniam omnis tempora."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
