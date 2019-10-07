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
      return {"slug":"cupiditate_voluptas","name":"Recusandae possimus id autem.","description":"Consequatur reprehenderit explicabo. Maiores maxime quos. Fuga eveniet sed.","price":90942.74,"header":"Dolorum aliquam ad laudantium.","footer":"Assumenda rerum qui fugiat.","moreInfo":"Facilis quia qui totam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
