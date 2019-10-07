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
      return {"slug":"optio_nesciunt","name":"Delectus cupiditate eaque ex.","description":"Unde et deleniti. Et totam delectus. Iste et quod.","price":87873.54,"header":"Illo dicta deserunt est.","footer":"Et aliquid et quis.","moreInfo":"Amet voluptatem omnis ex."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
