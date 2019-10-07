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
      return {"slug":"iusto_omnis","name":"Porro cumque consectetur corrupti.","description":"Quia cupiditate et. Est nesciunt voluptas. Reiciendis animi sit.","price":41357.55,"header":"Dicta vitae quas et.","footer":"Omnis dolores optio in.","moreInfo":"Aspernatur et esse aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
