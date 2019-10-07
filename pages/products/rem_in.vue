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
      return {"slug":"rem_in","name":"Aut ipsam sunt ratione.","description":"Exercitationem eveniet molestiae. Voluptate ipsa soluta. In et fugiat.","price":82376.99,"header":"Ut voluptatem quas quo.","footer":"Sequi omnis reprehenderit quasi.","moreInfo":"Ipsa atque aut delectus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
