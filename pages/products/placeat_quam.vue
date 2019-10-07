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
      return {"slug":"placeat_quam","name":"Sit fuga molestias dignissimos.","description":"Voluptatem accusamus molestias. Modi voluptas corrupti. Facere omnis maiores.","price":84368.23,"header":"Atque consequatur placeat est.","footer":"Consequatur iure voluptas non.","moreInfo":"Quod id molestiae enim."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
