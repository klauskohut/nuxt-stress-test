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
      return {"slug":"exercitationem_ut","name":"Sed aut placeat dolor.","description":"Incidunt facere qui. Incidunt sequi ut. Omnis ut nemo.","price":84114.41,"header":"Ratione ipsam sunt omnis.","footer":"Sed ullam sit deserunt.","moreInfo":"Est ullam eum natus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
