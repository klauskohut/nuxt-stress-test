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
      return {"slug":"quibusdam-animi","name":"Impedit nam et corrupti.","description":"Vel dolorum provident. Id in rem. Est omnis maiores.","price":68698.62,"header":"Blanditiis non reiciendis et.","footer":"Autem dicta error sunt.","moreInfo":"Repudiandae non consequatur fugit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
