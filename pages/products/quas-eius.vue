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
      return {"slug":"quas-eius","name":"Quas est aut laborum.","description":"Rerum pariatur eligendi. Minima quidem ut. Labore quod placeat.","price":47573.07,"header":"Et ab autem magni.","footer":"Id ea repellendus et.","moreInfo":"Nisi modi suscipit cumque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
