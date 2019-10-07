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
      return {"slug":"id_distinctio","name":"Assumenda quisquam et enim.","description":"Rem vero aut. Possimus qui expedita. Nemo ipsam voluptatibus.","price":91940.91,"header":"Cumque rerum velit ut.","footer":"Cum cumque consequatur ipsum.","moreInfo":"Rerum aliquam a tenetur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
