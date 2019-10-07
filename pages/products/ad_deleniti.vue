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
      return {"slug":"ad_deleniti","name":"Eaque atque alias labore.","description":"Recusandae qui eum. Placeat iusto sequi. Dignissimos quia nulla.","price":49779.06,"header":"Eum nihil enim soluta.","footer":"Ipsum accusantium alias numquam.","moreInfo":"Labore beatae et maiores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
