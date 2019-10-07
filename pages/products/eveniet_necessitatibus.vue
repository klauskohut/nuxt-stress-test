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
      return {"slug":"eveniet_necessitatibus","name":"Deserunt non iure temporibus.","description":"Ipsam ut quasi. Error omnis earum. Labore hic adipisci.","price":54889.96,"header":"Ex suscipit consequuntur natus.","footer":"Non aliquid sunt sit.","moreInfo":"Error culpa placeat et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
