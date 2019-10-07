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
      return {"slug":"doloribus-aut","name":"Beatae consequuntur alias nulla.","description":"In magnam officiis. Quisquam dolor repellat. Repellat sed qui.","price":94132.66,"header":"Id voluptatibus aliquid molestiae.","footer":"Provident at optio voluptas.","moreInfo":"Ipsam quia ullam hic."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
