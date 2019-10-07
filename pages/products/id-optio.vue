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
      return {"slug":"id-optio","name":"Enim reiciendis nihil quos.","description":"Eius voluptatem cum. Aut necessitatibus distinctio. Quae eligendi facilis.","price":78671.75,"header":"Hic nihil consequatur laborum.","footer":"Animi libero a sint.","moreInfo":"Maiores maxime non omnis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
