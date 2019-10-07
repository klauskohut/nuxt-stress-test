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
      return {"slug":"quia_quo","name":"Dolorem accusamus porro animi.","description":"Voluptate facilis dignissimos. Placeat omnis sint. Ea reiciendis natus.","price":77528.18,"header":"Optio odio voluptates perspiciatis.","footer":"Nobis ut sint ratione.","moreInfo":"Cumque voluptatibus dolore accusantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
