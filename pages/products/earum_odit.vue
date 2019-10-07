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
      return {"slug":"earum_odit","name":"Quaerat rerum odit praesentium.","description":"Quia ex vitae. Et est dicta. Voluptatibus ab voluptate.","price":34651.18,"header":"Cum architecto temporibus omnis.","footer":"Rerum vel nisi voluptatum.","moreInfo":"Odio veritatis qui magnam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
