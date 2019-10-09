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
      return {"slug":"et_quae","name":"Aliquam quia quod repellendus.","description":"Qui ipsum quis. In non quidem. Culpa consequatur pariatur.","price":93437.59,"header":"Recusandae error culpa iusto.","footer":"Voluptas quasi sit adipisci.","moreInfo":"Natus aut voluptas nemo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
