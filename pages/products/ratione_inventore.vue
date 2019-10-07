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
      return {"slug":"ratione_inventore","name":"Et cum animi quia.","description":"Sequi sunt ut. Ut sint architecto. Et et dolores.","price":16641.85,"header":"Rerum rem occaecati soluta.","footer":"Aut eum atque quod.","moreInfo":"Molestiae quidem consequatur vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
