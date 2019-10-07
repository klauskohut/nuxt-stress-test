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
      return {"slug":"corrupti-natus","name":"Sit amet voluptas quaerat.","description":"Aspernatur facilis voluptatum. Doloremque recusandae dolor. Cupiditate voluptatibus odio.","price":95503.73,"header":"Exercitationem quasi velit nulla.","footer":"Dolorem omnis asperiores corporis.","moreInfo":"Voluptatem a unde fugit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
