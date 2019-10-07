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
      return {"slug":"nemo-dolores","name":"Quod nihil quo et.","description":"Voluptatem modi et. Occaecati reprehenderit molestias. Maiores ullam explicabo.","price":98932.47,"header":"Non quis molestiae mollitia.","footer":"Quo illum consequatur consectetur.","moreInfo":"Consequuntur qui inventore dicta."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
