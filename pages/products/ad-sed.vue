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
      return {"slug":"ad-sed","name":"Ipsa et voluptates sapiente.","description":"Architecto et veniam. Ducimus voluptatibus eligendi. Minima officia earum.","price":73840.65,"header":"Quis consequatur odit molestias.","footer":"Quas incidunt optio blanditiis.","moreInfo":"Quibusdam ea nam beatae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
