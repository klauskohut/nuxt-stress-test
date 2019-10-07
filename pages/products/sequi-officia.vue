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
      return {"slug":"sequi-officia","name":"Quas aliquam quos soluta.","description":"Aut ut occaecati. Tenetur omnis nihil. In iusto impedit.","price":67562.37,"header":"Odit ut praesentium deserunt.","footer":"Voluptatibus neque voluptatem inventore.","moreInfo":"Nostrum temporibus minima impedit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
