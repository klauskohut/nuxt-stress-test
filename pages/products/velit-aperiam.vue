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
      return {"slug":"velit-aperiam","name":"Repellendus sequi excepturi dolor.","description":"Voluptatem ipsam dolores. Numquam nostrum et. Quam possimus ut.","price":18926.27,"header":"Molestiae illo eos sit.","footer":"Enim quam voluptatibus nihil.","moreInfo":"Quia dolor quisquam molestias."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
