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
      return {"slug":"qui_ut","name":"Ut qui ab culpa.","description":"Unde sit non. Et sunt molestiae. Incidunt distinctio accusamus.","price":66712.77,"header":"Quod ut quia ut.","footer":"Nulla reiciendis aspernatur saepe.","moreInfo":"Minima debitis sint eveniet."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
