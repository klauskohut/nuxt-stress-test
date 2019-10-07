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
      return {"slug":"ipsam-fugiat","name":"Quia dolores reiciendis aliquam.","description":"Ex rerum perspiciatis. Reprehenderit minima deleniti. Repellat aut eos.","price":43276.56,"header":"Velit quasi esse nihil.","footer":"Officia corporis architecto adipisci.","moreInfo":"Adipisci voluptates dolorem consequuntur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
