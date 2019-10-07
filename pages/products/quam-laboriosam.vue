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
      return {"slug":"quam-laboriosam","name":"Qui quam sit provident.","description":"Ullam incidunt molestiae. Laborum culpa minus. Ipsum illo libero.","price":35014.17,"header":"Sapiente aliquid perspiciatis reprehenderit.","footer":"Ut omnis delectus voluptatem.","moreInfo":"Repellat reprehenderit consequatur enim."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
