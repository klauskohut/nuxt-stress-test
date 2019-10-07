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
      return {"slug":"facere_et","name":"Sit voluptates delectus alias.","description":"Repellat iure dignissimos. Qui laboriosam aliquam. Id molestiae nisi.","price":94442.87,"header":"Molestiae quibusdam ea enim.","footer":"Pariatur error sit maiores.","moreInfo":"Minus sed sint magni."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
