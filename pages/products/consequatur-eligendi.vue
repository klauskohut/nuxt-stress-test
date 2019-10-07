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
      return {"slug":"consequatur-eligendi","name":"Mollitia nihil ab sed.","description":"Perferendis voluptatem autem. Aperiam totam quia. Ipsum minus autem.","price":32565.14,"header":"Sit illum culpa autem.","footer":"Id ipsam nam dolorum.","moreInfo":"Autem blanditiis magnam sed."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
