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
      return {"slug":"enim-eos","name":"Quis atque consequatur veniam.","description":"Vero voluptates nihil. Neque molestiae laboriosam. Omnis fugiat eligendi.","price":65561.73,"header":"Culpa dicta sunt quam.","footer":"Nesciunt doloribus illo necessitatibus.","moreInfo":"Dolor dolores ut nihil."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
