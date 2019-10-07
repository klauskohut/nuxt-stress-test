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
      return {"slug":"quo-corrupti","name":"Voluptate hic illo molestias.","description":"Sit rerum provident. Quam explicabo quia. Eos ad itaque.","price":19164.29,"header":"Sed quod adipisci nesciunt.","footer":"Quidem voluptate est provident.","moreInfo":"In a rerum illum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
