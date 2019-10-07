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
      return {"slug":"et_similique","name":"Et dolor laborum non.","description":"Commodi corporis minus. Quia porro illum. Quo pariatur labore.","price":43978.62,"header":"Eum quia ducimus assumenda.","footer":"Suscipit doloremque autem et.","moreInfo":"Alias perspiciatis sit voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
