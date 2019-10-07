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
      return {"slug":"incidunt-ut","name":"Doloribus natus autem id.","description":"Facilis sit est. Quia maxime qui. Delectus magnam neque.","price":56242.62,"header":"Neque voluptatem quis doloremque.","footer":"Odio quibusdam in assumenda.","moreInfo":"Cumque eum iusto quis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
