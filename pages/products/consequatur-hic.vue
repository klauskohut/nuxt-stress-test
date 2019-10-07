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
      return {"slug":"consequatur-hic","name":"Porro omnis quae deleniti.","description":"Repudiandae ea harum. Est quae consequatur. Ipsum sint suscipit.","price":38969.19,"header":"Omnis vel rerum necessitatibus.","footer":"In placeat nesciunt ipsum.","moreInfo":"Laboriosam dolor doloribus occaecati."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
