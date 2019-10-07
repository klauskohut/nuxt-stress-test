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
      return {"slug":"et_velit","name":"Aut sit rerum unde.","description":"Itaque nam ducimus. Ut qui harum. Optio aspernatur numquam.","price":95151.88,"header":"Eos ex alias aut.","footer":"Distinctio reiciendis earum quasi.","moreInfo":"Neque sed voluptatibus minus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
