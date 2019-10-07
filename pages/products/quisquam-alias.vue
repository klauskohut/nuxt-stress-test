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
      return {"slug":"quisquam-alias","name":"Dolorum nobis harum illo.","description":"Tempora sunt et. Quae voluptates molestiae. Et facilis doloremque.","price":32379.68,"header":"Nostrum fugiat nihil blanditiis.","footer":"Magnam asperiores alias deleniti.","moreInfo":"Non qui enim occaecati."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
