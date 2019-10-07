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
      return {"slug":"consectetur-quidem","name":"Quidem ipsa et qui.","description":"Et alias veritatis. Eaque dolorum omnis. Neque esse dignissimos.","price":52683.37,"header":"Ex doloribus qui maiores.","footer":"Quisquam exercitationem rerum voluptatem.","moreInfo":"Non voluptates consequatur voluptatum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
