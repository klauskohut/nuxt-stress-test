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
      return {"slug":"quam-eum","name":"Architecto illo voluptas mollitia.","description":"Dicta cum et. Magni sit ut. Quia eos similique.","price":43099.96,"header":"Veritatis iste aperiam et.","footer":"Inventore impedit nemo vero.","moreInfo":"Perspiciatis ut libero quae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
