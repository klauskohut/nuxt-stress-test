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
      return {"slug":"est_fugiat","name":"Magni ratione consequatur voluptate.","description":"Rerum voluptates omnis. Nobis blanditiis minima. Vel aut nulla.","price":41692.61,"header":"Dolores provident nesciunt a.","footer":"Provident ab ipsam quas.","moreInfo":"Enim mollitia et ratione."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
