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
      return {"slug":"cupiditate-adipisci","name":"Sint et tempore error.","description":"Saepe molestias qui. Aut accusamus ea. Ad illo ducimus.","price":56385.86,"header":"Rem sunt dicta pariatur.","footer":"Autem perspiciatis culpa hic.","moreInfo":"Ex aliquam laborum rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
