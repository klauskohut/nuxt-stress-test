<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <Slider />
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  import Slider from '../../components/Slider'

  export default {
    layout: 'product',
    components: {
      Product,
      Slider
    },
    data() {
      return {"slug":"optio-in","name":"Sit qui sit ut.","description":"Est iusto illo. Doloremque ipsa cum. Voluptate recusandae assumenda.","price":67189.24,"header":"Esse doloribus dolorem velit.","footer":"Doloremque aut dolorem tempore.","moreInfo":"Fugiat fugit porro debitis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
