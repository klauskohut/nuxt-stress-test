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
      return {"slug":"nam-id","name":"Aliquam rerum voluptatem nihil.","description":"Eos vel laboriosam. Distinctio nesciunt unde. Rerum sed voluptatibus.","price":11691.84,"header":"Et ut dolores id.","footer":"Quod non praesentium impedit.","moreInfo":"Ea qui et sit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
