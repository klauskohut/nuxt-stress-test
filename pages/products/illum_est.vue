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
      return {"slug":"illum_est","name":"Eveniet et suscipit repellat.","description":"Aut asperiores fugit. Voluptatem laborum aperiam. Magni nobis iste.","price":60721.05,"header":"Ea facilis eveniet nulla.","footer":"Ipsam laborum ad ipsum.","moreInfo":"Ratione quas dignissimos quisquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
