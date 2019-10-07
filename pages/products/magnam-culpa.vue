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
      return {"slug":"magnam-culpa","name":"Repellat asperiores iste recusandae.","description":"Reiciendis itaque asperiores. Rerum praesentium et. Ea rerum neque.","price":61182.86,"header":"Unde eum facere fugit.","footer":"Eum vero odio cupiditate.","moreInfo":"Dignissimos voluptatem quos voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
