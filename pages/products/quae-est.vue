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
      return {"slug":"quae-est","name":"Voluptatem sunt molestiae sint.","description":"Asperiores aut hic. Corporis eum est. Enim error voluptates.","price":23480.08,"header":"Atque esse minus numquam.","footer":"Ea necessitatibus ad eos.","moreInfo":"Debitis totam qui at."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
