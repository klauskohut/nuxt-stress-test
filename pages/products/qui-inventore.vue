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
      return {"slug":"qui-inventore","name":"Hic doloribus sapiente in.","description":"Facilis eos est. Repellat ipsam at. Quo est mollitia.","price":18859.04,"header":"Sunt animi cupiditate hic.","footer":"Est voluptas deserunt quia.","moreInfo":"Fugit velit eos quae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
