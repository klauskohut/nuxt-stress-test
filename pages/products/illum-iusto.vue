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
      return {"slug":"illum-iusto","name":"Perferendis qui sed sint.","description":"Error veritatis enim. Quis magni ad. Impedit omnis qui.","price":22635.68,"header":"Beatae voluptatibus laudantium perspiciatis.","footer":"Quam ut veniam minus.","moreInfo":"Ex labore delectus cupiditate."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
