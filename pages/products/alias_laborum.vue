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
      return {"slug":"alias_laborum","name":"Nulla sit est quis.","description":"Libero sit quia. Modi tempore cum. Beatae quod et.","price":75445.74,"header":"Sapiente expedita hic earum.","footer":"Id dicta sint molestiae.","moreInfo":"Facilis inventore repellendus quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
