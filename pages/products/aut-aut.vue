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
      return {"slug":"aut-aut","name":"Nemo nulla fugit est.","description":"Repudiandae officiis eum. Sed nihil vel. Exercitationem adipisci voluptates.","price":86145.81,"header":"Optio ut dicta architecto.","footer":"Facere repellendus voluptatem omnis.","moreInfo":"Eligendi rerum ea maiores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
