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
      return {"slug":"consectetur_voluptatem","name":"Ratione commodi quis fugiat.","description":"Aut temporibus est. Reprehenderit expedita deleniti. Amet beatae eligendi.","price":22160.84,"header":"Ut ut dolor explicabo.","footer":"Et magni repellat molestias.","moreInfo":"Id et et ducimus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
