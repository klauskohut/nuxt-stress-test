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
      return {"slug":"aut_eius","name":"Dicta officia consequatur rerum.","description":"Perferendis culpa suscipit. Eos quia rerum. Atque laudantium sequi.","price":25376.52,"header":"Rem inventore quo optio.","footer":"In nihil quaerat voluptatem.","moreInfo":"Sequi cupiditate laboriosam voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
