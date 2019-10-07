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
      return {"slug":"commodi_ullam","name":"Rerum fugit voluptas perferendis.","description":"Esse omnis dolorem. Unde ducimus esse. Mollitia suscipit eaque.","price":58563.76,"header":"Error dolore culpa eum.","footer":"Animi eos aliquam consectetur.","moreInfo":"Porro omnis voluptas vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
