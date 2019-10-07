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
      return {"slug":"in-at","name":"Quis ducimus et eligendi.","description":"Maxime voluptatem fugit. Quam commodi deleniti. A perferendis excepturi.","price":47811.05,"header":"Sint et voluptatem velit.","footer":"Et facere unde corporis.","moreInfo":"Quam ad nihil laboriosam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
