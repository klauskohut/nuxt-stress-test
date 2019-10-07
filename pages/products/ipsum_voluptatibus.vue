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
      return {"slug":"ipsum_voluptatibus","name":"Et eligendi perspiciatis pariatur.","description":"Dicta iusto hic. Et sint aperiam. Iure quia at.","price":18687.96,"header":"Quas et rem ex.","footer":"Vel aut a consectetur.","moreInfo":"Id est accusamus mollitia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
