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
      return {"slug":"sunt_quaerat","name":"Laudantium hic qui dicta.","description":"Quia eos tenetur. Sint alias sequi. Praesentium est quam.","price":69655.15,"header":"Autem eligendi saepe beatae.","footer":"Sunt et autem assumenda.","moreInfo":"Id et voluptas officiis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
