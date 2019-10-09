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
      return {"slug":"dignissimos-provident","name":"Cum porro consequatur culpa.","description":"Molestiae illo accusamus. Rerum cumque atque. Aut quos minus.","price":20030.89,"header":"Illo velit praesentium a.","footer":"Ex nihil et sapiente.","moreInfo":"Delectus accusantium et nam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
