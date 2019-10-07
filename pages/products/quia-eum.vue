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
      return {"slug":"quia-eum","name":"Aliquam mollitia illo aut.","description":"Natus reprehenderit est. Asperiores vel est. Nihil suscipit non.","price":72556.29,"header":"Sunt velit et nihil.","footer":"Maxime excepturi eaque voluptatem.","moreInfo":"Pariatur totam ea nulla."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
