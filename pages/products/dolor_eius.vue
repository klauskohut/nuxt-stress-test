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
      return {"slug":"dolor_eius","name":"Nam veniam voluptas qui.","description":"Sapiente officiis odio. Magni ullam saepe. Quidem et et.","price":75221.36,"header":"Ut minima molestiae velit.","footer":"Ad vero maxime soluta.","moreInfo":"Aut quae nostrum minus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
