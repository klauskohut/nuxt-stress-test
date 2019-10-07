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
      return {"slug":"omnis-reiciendis","name":"Quos doloremque tempore ullam.","description":"Fugiat vitae aut. Et ut itaque. Et iusto ipsam.","price":63297.26,"header":"Eius rerum quia laborum.","footer":"Reprehenderit veniam natus autem.","moreInfo":"Consequatur quas cupiditate omnis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
