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
      return {"slug":"voluptate_natus","name":"Nostrum quisquam magnam assumenda.","description":"Debitis commodi porro. Qui esse ut. Modi illo explicabo.","price":53718.16,"header":"Qui autem quas voluptatum.","footer":"Quis cupiditate quisquam autem.","moreInfo":"Animi magni ratione incidunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
