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
      return {"slug":"nam-recusandae","name":"Soluta et iste cumque.","description":"Sit veritatis et. Voluptas est explicabo. Praesentium cum dolore.","price":43826.43,"header":"Sunt autem quisquam architecto.","footer":"Autem quo animi sit.","moreInfo":"Doloribus ullam nulla voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
