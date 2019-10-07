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
      return {"slug":"ut_et","name":"Asperiores qui blanditiis officiis.","description":"Laudantium aliquid corrupti. Rerum adipisci mollitia. Expedita rerum et.","price":96850.78,"header":"Consequatur expedita molestias qui.","footer":"Quidem deleniti delectus et.","moreInfo":"Dolorum id reiciendis voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
