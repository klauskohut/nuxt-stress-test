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
      return {"slug":"sapiente-rerum","name":"Minima soluta commodi ut.","description":"Laborum maiores cum. Tempora velit rem. Fugiat rerum voluptatem.","price":19024.65,"header":"Repellat quisquam totam reprehenderit.","footer":"Eligendi deserunt est sed.","moreInfo":"Nesciunt occaecati dicta nihil."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
