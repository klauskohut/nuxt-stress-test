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
      return {"slug":"autem_aut","name":"Beatae ab odio porro.","description":"Molestiae quidem enim. Cupiditate enim rem. Quos natus nisi.","price":84432.19,"header":"Possimus laudantium et nesciunt.","footer":"Quis voluptatem consequuntur ut.","moreInfo":"Et voluptates accusamus accusantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
