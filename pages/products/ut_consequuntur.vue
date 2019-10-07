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
      return {"slug":"ut_consequuntur","name":"Sed maiores incidunt dolorem.","description":"Saepe placeat corporis. Nesciunt pariatur et. Iure aut sunt.","price":98331.66,"header":"Et beatae occaecati quod.","footer":"Est labore laborum magnam.","moreInfo":"Maiores nulla tempore ipsam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
