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
      return {"slug":"doloremque-nemo","name":"Quos ut non labore.","description":"Neque assumenda fugiat. Consectetur molestiae et. Quam minus repudiandae.","price":81819.31,"header":"Est consequatur sunt doloremque.","footer":"Et quasi nulla maxime.","moreInfo":"Neque placeat quibusdam repellendus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
