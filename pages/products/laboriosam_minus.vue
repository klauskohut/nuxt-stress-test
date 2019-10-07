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
      return {"slug":"laboriosam_minus","name":"Distinctio quo tempore aperiam.","description":"Pariatur qui ipsa. Unde debitis voluptatem. Voluptates ut dolor.","price":79750.37,"header":"Quo similique nisi quod.","footer":"Qui impedit reiciendis autem.","moreInfo":"Omnis nesciunt dolor eveniet."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
