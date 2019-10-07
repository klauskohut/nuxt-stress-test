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
      return {"slug":"sint-tempore","name":"Impedit dolorem doloremque ut.","description":"Enim omnis vitae. Ratione cum illo. Inventore officia harum.","price":54723.18,"header":"Maiores nam alias explicabo.","footer":"Repudiandae rerum et temporibus.","moreInfo":"Aliquam provident in eos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
