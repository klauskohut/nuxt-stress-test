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
      return {"slug":"eligendi-qui","name":"Veritatis voluptatem et voluptatibus.","description":"Sint error quaerat. Dolor sint sit. Voluptatem reiciendis nisi.","price":90887.14,"header":"Doloremque rem saepe amet.","footer":"Quam illo iste est.","moreInfo":"In occaecati et autem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
