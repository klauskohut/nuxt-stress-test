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
      return {"slug":"assumenda_voluptas","name":"Ratione esse distinctio temporibus.","description":"Aut consequatur exercitationem. Adipisci soluta sequi. Voluptatem aut reprehenderit.","price":47018.62,"header":"Excepturi expedita explicabo quia.","footer":"Eligendi officiis porro quisquam.","moreInfo":"Voluptatum vel et quo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
