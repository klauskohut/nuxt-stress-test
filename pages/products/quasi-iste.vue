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
      return {"slug":"quasi-iste","name":"Vitae quas molestias magnam.","description":"Sunt rerum placeat. Ipsa architecto enim. Rem quibusdam eligendi.","price":15392.45,"header":"Nemo labore corrupti sed.","footer":"Nisi eligendi iusto et.","moreInfo":"Nisi modi voluptates natus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
