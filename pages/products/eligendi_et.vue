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
      return {"slug":"eligendi_et","name":"Aut quaerat fuga laborum.","description":"Perferendis voluptatem similique. Ipsam voluptates officiis. Natus commodi dolor.","price":99313.13,"header":"Unde maxime suscipit temporibus.","footer":"Nobis perferendis fugit deleniti.","moreInfo":"Eum nostrum repellat consectetur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
