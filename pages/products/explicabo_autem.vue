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
      return {"slug":"explicabo_autem","name":"Assumenda aut voluptas a.","description":"Blanditiis culpa veritatis. Facilis rerum qui. Dolores totam ipsum.","price":27992.44,"header":"Sit vero reprehenderit et.","footer":"Quo eum dolor molestias.","moreInfo":"Sapiente maxime suscipit id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
