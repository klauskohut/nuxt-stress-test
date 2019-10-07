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
      return {"slug":"veniam_animi","name":"Explicabo velit minus temporibus.","description":"Autem qui incidunt. In et et. Voluptates quis dolorum.","price":69498.88,"header":"Quia neque sint modi.","footer":"Aut non consequatur esse.","moreInfo":"Vel quo quidem autem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
