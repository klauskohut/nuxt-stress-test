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
      return {"slug":"perspiciatis-enim","name":"Sit tempore assumenda nobis.","description":"Dolore dicta sint. Ipsum totam rem. Aut praesentium animi.","price":35643.15,"header":"Omnis consectetur pariatur voluptatem.","footer":"Aut illum sed reprehenderit.","moreInfo":"Libero molestias eos id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
