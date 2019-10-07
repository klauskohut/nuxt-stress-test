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
      return {"slug":"inventore-voluptatem","name":"Aut molestias unde tenetur.","description":"Et quas et. Est et laboriosam. Maiores vel ut.","price":42682.57,"header":"Culpa est qui non.","footer":"Ipsum iure libero autem.","moreInfo":"Nulla molestias quam ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
