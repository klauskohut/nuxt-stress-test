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
      return {"slug":"molestiae_eos","name":"Eligendi quo placeat distinctio.","description":"In dolores quasi. Qui quidem error. Velit voluptatem inventore.","price":88666.14,"header":"Totam ex maiores aut.","footer":"Ipsam qui rerum numquam.","moreInfo":"Vero dolorem similique non."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
