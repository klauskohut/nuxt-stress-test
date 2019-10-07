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
      return {"slug":"iusto_sapiente","name":"Assumenda quis fuga expedita.","description":"Sit quia eos. Eum quo architecto. Omnis commodi illo.","price":67528.43,"header":"Est accusamus odio aut.","footer":"Asperiores veritatis ut placeat.","moreInfo":"Est nihil qui dicta."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
