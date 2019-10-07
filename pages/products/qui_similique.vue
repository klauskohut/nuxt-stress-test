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
      return {"slug":"qui_similique","name":"Fuga repellat eveniet harum.","description":"Vel vitae facere. In fugiat veritatis. Architecto ut et.","price":40736.53,"header":"Vitae nulla ut illum.","footer":"Quis impedit quasi rerum.","moreInfo":"Voluptas sint quis est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
