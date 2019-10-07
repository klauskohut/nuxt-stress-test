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
      return {"slug":"omnis_iusto","name":"Voluptatem sunt enim debitis.","description":"Sit quas cumque. Quaerat sequi distinctio. Cupiditate sint aliquid.","price":28895.01,"header":"Esse sint deleniti officia.","footer":"Facilis et quas qui.","moreInfo":"Suscipit alias molestiae minus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
