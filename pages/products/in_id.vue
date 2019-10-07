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
      return {"slug":"in_id","name":"Incidunt cum ut vel.","description":"Reiciendis commodi vitae. Inventore recusandae iusto. Ut voluptatem sint.","price":66972.58,"header":"Voluptatem voluptates nobis aut.","footer":"Dolorem sequi rerum cumque.","moreInfo":"Omnis dolorum laudantium ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
