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
      return {"slug":"cumque-voluptatem","name":"Architecto incidunt mollitia quo.","description":"Optio officia et. Quia quis temporibus. Sunt et veritatis.","price":74258.99,"header":"Ratione et aut est.","footer":"Nobis exercitationem maiores ratione.","moreInfo":"Voluptate debitis quidem saepe."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
