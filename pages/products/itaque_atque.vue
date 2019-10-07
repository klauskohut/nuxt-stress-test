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
      return {"slug":"itaque_atque","name":"Autem quidem consequuntur eos.","description":"Hic voluptates nam. Dolorem soluta ut. Dolor aut nobis.","price":60748.03,"header":"Consectetur vero blanditiis accusamus.","footer":"Ut voluptas vitae voluptas.","moreInfo":"Et saepe error consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
