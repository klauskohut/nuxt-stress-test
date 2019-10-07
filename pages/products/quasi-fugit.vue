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
      return {"slug":"quasi-fugit","name":"Et qui amet et.","description":"Quo impedit et. Tempore ratione et. Veritatis voluptate omnis.","price":25360.74,"header":"Voluptas sit sit atque.","footer":"Temporibus expedita quidem dolorem.","moreInfo":"Corrupti pariatur facere autem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
