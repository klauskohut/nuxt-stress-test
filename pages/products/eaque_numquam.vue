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
      return {"slug":"eaque_numquam","name":"Et recusandae enim aliquam.","description":"Et iste corporis. Pariatur et nemo. Omnis aut aut.","price":16112.09,"header":"Earum mollitia ut inventore.","footer":"Et ea possimus sint.","moreInfo":"Beatae vel est numquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
