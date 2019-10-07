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
      return {"slug":"natus_ut","name":"Et alias veniam quod.","description":"Repudiandae recusandae magni. At porro dolorum. Voluptatibus vitae doloremque.","price":53902.59,"header":"Dignissimos laboriosam est quidem.","footer":"Voluptas est necessitatibus sunt.","moreInfo":"Sunt ut deserunt similique."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
