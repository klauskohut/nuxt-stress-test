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
      return {"slug":"provident-mollitia","name":"Id sit culpa impedit.","description":"Qui at aperiam. Laborum quam culpa. Asperiores unde tenetur.","price":40031.88,"header":"Quia officia illum velit.","footer":"Rerum aliquam distinctio nulla.","moreInfo":"Labore dolorum distinctio aliquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
