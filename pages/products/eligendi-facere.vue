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
      return {"slug":"eligendi-facere","name":"Enim saepe sunt est.","description":"Distinctio omnis magnam. Sint voluptate numquam. In quod dolor.","price":43480.19,"header":"Est autem aliquid ea.","footer":"Id voluptatem quasi architecto.","moreInfo":"Quaerat aut hic vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
