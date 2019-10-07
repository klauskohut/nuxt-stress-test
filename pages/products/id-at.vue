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
      return {"slug":"id-at","name":"Omnis facere error non.","description":"Quia ea fugiat. Voluptatem ratione adipisci. Est eius alias.","price":35190.43,"header":"Aliquam autem distinctio cupiditate.","footer":"Consectetur commodi hic nesciunt.","moreInfo":"Aut sit accusantium dolores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
