<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  export default {
    layout: 'product',
    components: {
      Product,
    },
    data() {
      return {"slug":"at-et","name":"Autem et quibusdam est.","description":"Quae consequatur quis. Modi quod quis. Exercitationem et in.","price":70753.84,"header":"Consequuntur recusandae autem deleniti.","footer":"Tempora ad omnis ratione.","moreInfo":"Earum sapiente autem eos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
