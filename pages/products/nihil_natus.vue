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
      return {"slug":"nihil_natus","name":"Consequatur cumque quisquam nihil.","description":"Autem eius rem. Voluptatum et quo. Qui est sit.","price":68205.82,"header":"Aut dolorum natus dolorem.","footer":"Sit quidem beatae et.","moreInfo":"Et enim ut perferendis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
