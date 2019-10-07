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
      return {"slug":"consequatur_non","name":"Rem suscipit voluptas unde.","description":"Nihil suscipit totam. Aut quisquam repellendus. Reiciendis quo est.","price":15042.54,"header":"Quod tenetur sunt rerum.","footer":"Sapiente ut eius consectetur.","moreInfo":"Sit laudantium officia quis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
