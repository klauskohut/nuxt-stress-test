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
      return {"slug":"cumque-consequatur","name":"Dolor id molestiae ullam.","description":"Consequatur inventore velit. Facere asperiores autem. Beatae dicta reiciendis.","price":22310.38,"header":"Itaque sed alias nisi.","footer":"Minus ut ut officia.","moreInfo":"Culpa quo quidem et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
