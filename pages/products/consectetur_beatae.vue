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
      return {"slug":"consectetur_beatae","name":"Molestias quasi ad cumque.","description":"Nisi et sit. Totam minima vel. Et nihil nobis.","price":27676.26,"header":"Molestiae optio laudantium dolor.","footer":"Possimus sed ex optio.","moreInfo":"Dignissimos quia quia harum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
