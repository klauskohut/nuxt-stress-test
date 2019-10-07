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
      return {"slug":"similique-id","name":"Tempore aperiam sit totam.","description":"Blanditiis aliquid eligendi. Optio suscipit saepe. Odio quis vitae.","price":39375.33,"header":"Vitae laborum qui et.","footer":"Adipisci non animi quisquam.","moreInfo":"Illum nesciunt et velit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
