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
      return {"slug":"dolores_consequatur","name":"Consectetur fugiat sit et.","description":"Esse omnis voluptas. Ut sed temporibus. Mollitia temporibus odit.","price":77930.62,"header":"Et maiores vero ipsam.","footer":"Beatae et voluptas et.","moreInfo":"Alias quo modi rem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
