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
      return {"slug":"non_cupiditate","name":"Mollitia ullam magni laudantium.","description":"Dolorum reprehenderit nihil. Quos mollitia necessitatibus. Quia blanditiis ad.","price":57669.93,"header":"Corporis enim voluptas quod.","footer":"Officiis omnis illo nulla.","moreInfo":"Nisi vitae eos enim."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
