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
      return {"slug":"et-vero","name":"Eaque aliquam maxime minima.","description":"Incidunt dolorum sed. Et est harum. Esse laboriosam magnam.","price":22607.74,"header":"Voluptatibus autem qui laboriosam.","footer":"Provident deleniti sit aut.","moreInfo":"Et nulla qui ad."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
