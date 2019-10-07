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
      return {"slug":"et_sunt","name":"Quis accusantium eius labore.","description":"Earum voluptates rem. Eos nostrum qui. Qui laborum illum.","price":62080.49,"header":"Blanditiis facere voluptatum iusto.","footer":"Voluptas facere nisi est.","moreInfo":"Occaecati et accusamus consequuntur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
