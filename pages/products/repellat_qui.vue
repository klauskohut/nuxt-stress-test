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
      return {"slug":"repellat_qui","name":"Quae et blanditiis minus.","description":"Sunt odio sit. Magni soluta nobis. Doloremque velit voluptatibus.","price":24395.44,"header":"Quia quia illum voluptate.","footer":"Nostrum quo error nisi.","moreInfo":"Doloribus velit voluptatem cumque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
