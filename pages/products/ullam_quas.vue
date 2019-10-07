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
      return {"slug":"ullam_quas","name":"In amet vel quisquam.","description":"Nemo cupiditate laboriosam. Voluptates ipsa vel. Voluptatem numquam placeat.","price":39028.25,"header":"Minus aspernatur fugit quam.","footer":"Maxime perferendis praesentium consequuntur.","moreInfo":"Et cumque eos laborum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
