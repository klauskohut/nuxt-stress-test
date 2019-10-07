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
      return {"slug":"ut-sed","name":"Repudiandae molestiae rerum dolores.","description":"Eius fugit similique. Rem est et. Ut qui et.","price":17775.94,"header":"Atque explicabo necessitatibus quisquam.","footer":"Sapiente velit voluptatum nihil.","moreInfo":"Ipsum reprehenderit voluptatem ipsa."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
