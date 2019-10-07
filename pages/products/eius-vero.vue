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
      return {"slug":"eius-vero","name":"Tempore sed sit repudiandae.","description":"Voluptates itaque iusto. Aut suscipit eligendi. Ut quo tenetur.","price":27699.17,"header":"Nihil excepturi dignissimos id.","footer":"Dolores recusandae magni voluptas.","moreInfo":"Est quibusdam earum dolores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
