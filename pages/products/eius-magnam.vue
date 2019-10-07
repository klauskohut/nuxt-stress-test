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
      return {"slug":"eius-magnam","name":"Fugiat soluta in eligendi.","description":"Aperiam odit doloribus. Aut veritatis possimus. Sapiente est id.","price":71763.05,"header":"Dolor neque nihil necessitatibus.","footer":"Consequatur sed illum eos.","moreInfo":"Reiciendis rerum et doloribus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
