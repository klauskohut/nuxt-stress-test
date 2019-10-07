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
      return {"slug":"velit-aut","name":"Quasi vitae reprehenderit eius.","description":"Porro eaque omnis. Qui nemo ut. Ipsum quis iusto.","price":12435.34,"header":"Ea sed nihil ea.","footer":"Delectus dolorum quod aut.","moreInfo":"Veritatis laudantium vel aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
