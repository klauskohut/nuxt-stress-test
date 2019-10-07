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
      return {"slug":"aut-et","name":"Et vel et fugit.","description":"Deleniti deserunt mollitia. Fuga iure voluptatem. Asperiores velit et.","price":83115.44,"header":"Reprehenderit et nemo eum.","footer":"Facilis eum nihil est.","moreInfo":"Voluptas delectus blanditiis laudantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
