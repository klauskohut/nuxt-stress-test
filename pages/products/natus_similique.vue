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
      return {"slug":"natus_similique","name":"Ea impedit et fugiat.","description":"Ullam sequi nulla. Nulla at et. Et inventore qui.","price":26559.45,"header":"Et qui voluptatibus quis.","footer":"Enim laudantium labore molestias.","moreInfo":"Ipsam aliquam est similique."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
