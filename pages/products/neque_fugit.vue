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
      return {"slug":"neque_fugit","name":"Quas tenetur fugit in.","description":"Totam aspernatur quas. Qui omnis nostrum. Eos est ut.","price":32438.19,"header":"Est est cumque amet.","footer":"Dolore nostrum quia eos.","moreInfo":"Possimus ut ipsam cumque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
