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
      return {"slug":"eius-necessitatibus","name":"Est beatae et omnis.","description":"Voluptatum omnis perferendis. Reiciendis sint voluptas. Velit dicta ut.","price":93210.56,"header":"Fugiat assumenda molestiae dolor.","footer":"Non sunt iusto non.","moreInfo":"Quam quasi doloribus illum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
