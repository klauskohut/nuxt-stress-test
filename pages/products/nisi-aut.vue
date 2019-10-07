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
      return {"slug":"nisi-aut","name":"Rerum minus perspiciatis dolorum.","description":"Minima quo maiores. Est molestiae qui. Earum et nobis.","price":12342.82,"header":"Nihil suscipit dolorem saepe.","footer":"Sit praesentium porro aut.","moreInfo":"Fugit dolores officia consectetur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
