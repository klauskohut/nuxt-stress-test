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
      return {"slug":"fugit_voluptatem","name":"Laudantium maiores possimus unde.","description":"Repellendus quaerat neque. Consequatur omnis tempora. Modi dolorum itaque.","price":24302.43,"header":"Quidem molestiae ducimus commodi.","footer":"Vel adipisci molestiae rem.","moreInfo":"Omnis sapiente laborum nihil."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
