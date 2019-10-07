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
      return {"slug":"minima_eaque","name":"Deserunt tempore autem accusantium.","description":"Ratione autem tenetur. Aperiam suscipit beatae. In et repellendus.","price":48283.89,"header":"Est voluptatem quidem et.","footer":"Distinctio repudiandae ea voluptatibus.","moreInfo":"Molestiae magnam esse error."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
