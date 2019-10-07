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
      return {"slug":"eligendi-tempore","name":"Perspiciatis excepturi sit voluptatibus.","description":"Doloremque nihil dolores. In molestiae sit. Id sint placeat.","price":69509.05,"header":"Est voluptates autem enim.","footer":"Voluptatibus deserunt ad nihil.","moreInfo":"Omnis ipsum accusamus voluptatum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
