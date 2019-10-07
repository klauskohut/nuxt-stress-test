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
      return {"slug":"pariatur-soluta","name":"Quae pariatur quod eaque.","description":"Consectetur accusantium quia. Enim quo vel. Aut molestiae illum.","price":44638.23,"header":"Est et quo quidem.","footer":"Aliquam et et sequi.","moreInfo":"Tempore officiis ad rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
