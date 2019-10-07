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
      return {"slug":"tempore_distinctio","name":"Cupiditate pariatur commodi repudiandae.","description":"Voluptas est tempore. Eum nesciunt repellendus. Molestiae odio possimus.","price":38466.51,"header":"Natus quis in molestias.","footer":"Natus et facilis tenetur.","moreInfo":"Placeat fugiat esse a."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
