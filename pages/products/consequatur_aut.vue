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
      return {"slug":"consequatur_aut","name":"Nulla numquam laudantium voluptatem.","description":"Placeat assumenda officia. Illo ullam perspiciatis. Voluptatem aut omnis.","price":53769.39,"header":"Sit eos nisi natus.","footer":"Libero veritatis laudantium necessitatibus.","moreInfo":"Vero porro non sit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
