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
      return {"slug":"iste-corrupti","name":"Odio et beatae autem.","description":"Neque quibusdam minima. Velit veritatis quis. Quis a vitae.","price":28510.16,"header":"Consequatur aut corporis nihil.","footer":"Quia molestiae sunt quam.","moreInfo":"Quas sit animi ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
