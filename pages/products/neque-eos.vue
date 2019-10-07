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
      return {"slug":"neque-eos","name":"Voluptatem repudiandae quo aut.","description":"Velit molestias assumenda. Consequatur odit autem. Maiores voluptas expedita.","price":25337.98,"header":"A iusto soluta temporibus.","footer":"Explicabo ut neque aut.","moreInfo":"Aut sit amet tenetur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
