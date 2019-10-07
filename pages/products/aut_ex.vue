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
      return {"slug":"aut_ex","name":"Eos voluptatem rerum est.","description":"Distinctio eum similique. Similique eos assumenda. Sint explicabo facere.","price":71435.02,"header":"Id odio cum totam.","footer":"Et a nesciunt cum.","moreInfo":"Nostrum omnis autem necessitatibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
