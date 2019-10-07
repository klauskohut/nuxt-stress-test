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
      return {"slug":"quasi-atque","name":"A quisquam ullam molestiae.","description":"Ut nesciunt omnis. Molestias cupiditate ab. Quaerat impedit commodi.","price":94073.84,"header":"Non sunt hic qui.","footer":"Occaecati id qui asperiores.","moreInfo":"Harum culpa quia quibusdam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
