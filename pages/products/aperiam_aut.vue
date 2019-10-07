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
      return {"slug":"aperiam_aut","name":"Atque vel qui cumque.","description":"Praesentium error est. Nulla eligendi error. Nemo ab non.","price":58737.03,"header":"Eos voluptate dolores omnis.","footer":"Recusandae perferendis ut impedit.","moreInfo":"Enim excepturi provident alias."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
