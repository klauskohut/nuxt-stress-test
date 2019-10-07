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
      return {"slug":"quis_et","name":"Accusantium est dolorem quos.","description":"Animi vel corporis. Enim voluptates aut. Aspernatur consequatur aliquid.","price":42449.09,"header":"Totam exercitationem qui et.","footer":"Doloribus facere architecto dolore.","moreInfo":"Vero sit tenetur ipsum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
