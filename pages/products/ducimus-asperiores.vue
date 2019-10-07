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
      return {"slug":"ducimus-asperiores","name":"Rerum impedit soluta dolorem.","description":"Voluptatibus doloremque iure. Voluptatem dolorem ipsum. Alias voluptatem aut.","price":42923.41,"header":"Magni quam recusandae enim.","footer":"Sed pariatur vel doloremque.","moreInfo":"Magni velit est quaerat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
