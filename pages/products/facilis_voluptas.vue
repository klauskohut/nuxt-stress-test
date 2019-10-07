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
      return {"slug":"facilis_voluptas","name":"Nesciunt atque non ut.","description":"Tenetur quidem eum. Totam quas quo. Perferendis sed dolorem.","price":36197.83,"header":"Quidem modi eius et.","footer":"Rerum quia aperiam qui.","moreInfo":"Iure cum voluptate molestiae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
