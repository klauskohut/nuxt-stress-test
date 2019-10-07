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
      return {"slug":"modi-asperiores","name":"Porro et voluptate qui.","description":"Consectetur sit minus. Nemo consequatur corporis. Quis cumque architecto.","price":12049.26,"header":"Molestiae quasi sunt quo.","footer":"Pariatur et commodi dolorem.","moreInfo":"Non quia mollitia quis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
