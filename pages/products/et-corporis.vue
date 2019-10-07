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
      return {"slug":"et-corporis","name":"Sit quidem rerum error.","description":"Iste quia reprehenderit. Ut velit exercitationem. Aperiam aliquid aut.","price":77497.09,"header":"Est incidunt ipsum ratione.","footer":"Ipsum cumque officia quia.","moreInfo":"Nemo officia quibusdam voluptate."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
