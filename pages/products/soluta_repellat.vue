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
      return {"slug":"soluta_repellat","name":"Sit et quidem rerum.","description":"Perspiciatis harum nihil. Error asperiores voluptatem. Quibusdam quia et.","price":93405.92,"header":"Explicabo est qui voluptatibus.","footer":"Vitae labore placeat quam.","moreInfo":"Tempora eum non dolorum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
