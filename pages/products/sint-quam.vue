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
      return {"slug":"sint-quam","name":"Ut quidem quia ipsam.","description":"Nihil voluptas debitis. Beatae vel laboriosam. Enim autem cumque.","price":50189.38,"header":"Soluta deserunt deleniti quam.","footer":"Amet quia quas assumenda.","moreInfo":"Sunt dicta sequi temporibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
