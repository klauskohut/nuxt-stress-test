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
      return {"slug":"ut-et","name":"Eum sapiente et est.","description":"Autem hic est. Cupiditate est vel. Sed necessitatibus praesentium.","price":27892.11,"header":"Dolorem esse in qui.","footer":"Soluta neque autem repudiandae.","moreInfo":"Et soluta possimus vero."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
