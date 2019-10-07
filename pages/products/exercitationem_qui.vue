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
      return {"slug":"exercitationem_qui","name":"Quod qui autem nemo.","description":"Deserunt ipsa qui. Officia doloribus vitae. Officiis excepturi est.","price":85036.61,"header":"Praesentium similique fuga iste.","footer":"Natus et facere reiciendis.","moreInfo":"Fuga consequatur excepturi doloribus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
