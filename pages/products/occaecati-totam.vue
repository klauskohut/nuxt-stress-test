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
      return {"slug":"occaecati-totam","name":"Aut nam voluptatem quia.","description":"Aspernatur ut tempora. Odio provident eum. Eum molestias perspiciatis.","price":79769.63,"header":"Ratione voluptatem molestiae repellendus.","footer":"Explicabo aut adipisci voluptas.","moreInfo":"Velit sint aut at."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
