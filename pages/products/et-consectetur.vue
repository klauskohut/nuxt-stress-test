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
      return {"slug":"et-consectetur","name":"Officiis amet repellat non.","description":"Officiis velit rerum. Quis vel tempora. Quidem repellendus nostrum.","price":80800.92,"header":"Eveniet quisquam impedit nulla.","footer":"Tempore eligendi et dolorum.","moreInfo":"Ea ipsa fugit omnis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
