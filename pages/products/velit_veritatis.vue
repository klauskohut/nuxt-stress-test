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
      return {"slug":"velit_veritatis","name":"Aspernatur ut adipisci tempora.","description":"Corporis laudantium rerum. Et et accusantium. Atque dolores veniam.","price":76651.37,"header":"Et est itaque est.","footer":"Doloremque similique tenetur delectus.","moreInfo":"Sint necessitatibus accusamus ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
