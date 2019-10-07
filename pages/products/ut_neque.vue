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
      return {"slug":"ut_neque","name":"Saepe voluptas officia voluptas.","description":"Laborum consectetur eligendi. Temporibus illo unde. Enim officia et.","price":29272.65,"header":"Voluptas sit iure qui.","footer":"Culpa numquam voluptas aliquid.","moreInfo":"Molestiae consectetur reiciendis explicabo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
