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
      return {"slug":"laboriosam-neque","name":"Voluptatem error praesentium tempore.","description":"Consectetur et rerum. Praesentium error eum. Tempore animi ipsam.","price":57269.24,"header":"Et totam nostrum vel.","footer":"Ab est tempore rerum.","moreInfo":"Amet eos sapiente est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
