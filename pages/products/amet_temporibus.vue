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
      return {"slug":"amet_temporibus","name":"Animi eum reiciendis officiis.","description":"Quia quod autem. Fugiat numquam et. Ipsum odit ullam.","price":27725.94,"header":"Sit quod rerum et.","footer":"Veritatis voluptatem dolores esse.","moreInfo":"Quia nam tempore adipisci."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
