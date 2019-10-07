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
      return {"slug":"nesciunt_quia","name":"Et sed quisquam ducimus.","description":"Ex distinctio non. Quia quis quia. Non dolorem occaecati.","price":73416.02,"header":"Et maxime animi accusantium.","footer":"Quo corporis ab dolores.","moreInfo":"Perspiciatis sunt eos ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
