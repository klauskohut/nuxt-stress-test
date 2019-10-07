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
      return {"slug":"vero-debitis","name":"Ipsa exercitationem optio animi.","description":"Earum dolorum aliquid. Aut rerum eum. Dolorem est qui.","price":74288.04,"header":"Vitae esse neque iste.","footer":"Nisi perspiciatis illum incidunt.","moreInfo":"Perferendis maiores fugiat eveniet."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
