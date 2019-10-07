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
      return {"slug":"est-optio","name":"Tempora voluptatem iusto accusamus.","description":"Possimus eaque ea. Consectetur ipsa suscipit. Eius occaecati sit.","price":44212.26,"header":"Neque voluptatem placeat rerum.","footer":"Illum neque ipsum voluptas.","moreInfo":"Dolores reiciendis temporibus autem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
