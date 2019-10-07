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
      return {"slug":"voluptatum_provident","name":"Sit enim accusantium laboriosam.","description":"Explicabo in exercitationem. Nostrum vel labore. Dolorem voluptate perspiciatis.","price":13820.47,"header":"Facere omnis voluptatibus ut.","footer":"Ullam nihil minima deserunt.","moreInfo":"Qui modi reiciendis quam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
