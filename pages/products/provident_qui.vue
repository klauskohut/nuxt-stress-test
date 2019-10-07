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
      return {"slug":"provident_qui","name":"Sed ducimus provident voluptas.","description":"In praesentium est. Enim blanditiis molestiae. Nesciunt quisquam in.","price":58780.54,"header":"Velit ut et aspernatur.","footer":"Repellendus nam quo vero.","moreInfo":"Aut consequuntur excepturi natus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
