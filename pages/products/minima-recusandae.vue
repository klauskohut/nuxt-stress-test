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
      return {"slug":"minima-recusandae","name":"Id deleniti dolores molestias.","description":"Et sunt voluptate. Et ipsam odio. Neque praesentium dolor.","price":43477.15,"header":"Sit esse itaque tempora.","footer":"Quia sapiente ab rerum.","moreInfo":"Ipsum mollitia est sunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
