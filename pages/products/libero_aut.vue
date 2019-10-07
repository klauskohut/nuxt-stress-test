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
      return {"slug":"libero_aut","name":"Cum omnis iure dolore.","description":"Ratione commodi quia. Laboriosam aut molestias. Et consequatur est.","price":80746.74,"header":"Quisquam perferendis facere sequi.","footer":"Praesentium inventore cum ratione.","moreInfo":"Asperiores veritatis dolor vero."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
