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
      return {"slug":"ea-eos","name":"Occaecati dolor nihil maxime.","description":"Sit est ea. Et et qui. Et vel ut.","price":24209.86,"header":"Incidunt nostrum nobis quibusdam.","footer":"Quasi iure velit sequi.","moreInfo":"Cum velit repudiandae nisi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
