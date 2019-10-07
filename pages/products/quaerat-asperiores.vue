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
      return {"slug":"quaerat-asperiores","name":"Dignissimos ipsa qui labore.","description":"Dolores perferendis voluptas. Aspernatur ut quam. Delectus sint est.","price":24281.68,"header":"Eaque aperiam quis aut.","footer":"Consequuntur voluptatibus vel labore.","moreInfo":"Assumenda voluptate nihil libero."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
