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
      return {"slug":"qui-quos","name":"Nemo voluptatem aut tenetur.","description":"Dolorum inventore velit. Maiores delectus enim. Aut et accusantium.","price":24021.06,"header":"Adipisci et blanditiis autem.","footer":"Dolorem et nobis corrupti.","moreInfo":"Quisquam provident dignissimos vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
