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
      return {"slug":"aut_autem","name":"Eveniet consequatur reiciendis praesentium.","description":"Error exercitationem accusamus. Excepturi debitis aspernatur. Enim pariatur quia.","price":77614.08,"header":"Vitae eos distinctio et.","footer":"Sequi et repudiandae dolorum.","moreInfo":"Odio aut nihil id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
