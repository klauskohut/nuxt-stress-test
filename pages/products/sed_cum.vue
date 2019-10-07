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
      return {"slug":"sed_cum","name":"Non et rerum nostrum.","description":"Velit quos fugiat. Voluptas ipsum perferendis. Cum ratione nostrum.","price":57045.26,"header":"Ea veritatis est exercitationem.","footer":"Et dolor fugiat magnam.","moreInfo":"Quibusdam quasi sint et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
