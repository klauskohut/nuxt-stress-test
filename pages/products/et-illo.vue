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
      return {"slug":"et-illo","name":"Voluptatem nostrum possimus distinctio.","description":"Cupiditate ut accusamus. Qui corrupti autem. Tenetur fugiat delectus.","price":28115.02,"header":"Aliquam vitae expedita quae.","footer":"Est quas et qui.","moreInfo":"Velit minus repellat eos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
