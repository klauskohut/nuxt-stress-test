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
      return {"slug":"vero-facere","name":"Aspernatur consectetur dolorum commodi.","description":"Ducimus at quia. Nisi ex voluptas. Voluptatum consectetur ut.","price":50403.04,"header":"Nesciunt labore esse reprehenderit.","footer":"Sed harum et sit.","moreInfo":"Repellat quod quae modi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
