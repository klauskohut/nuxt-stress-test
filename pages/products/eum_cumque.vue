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
      return {"slug":"eum_cumque","name":"Sint qui quod vitae.","description":"Eaque ipsa qui. In id nisi. Quasi perferendis sed.","price":58673.42,"header":"Est voluptatem ut sit.","footer":"Enim animi quaerat quia.","moreInfo":"Nostrum reprehenderit laboriosam voluptatum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
