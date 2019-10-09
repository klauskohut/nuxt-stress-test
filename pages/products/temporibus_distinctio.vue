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
      return {"slug":"temporibus_distinctio","name":"Vel voluptatem expedita quidem.","description":"Quae maxime nihil. Cupiditate sint quos. Aperiam eos maiores.","price":52229.09,"header":"Harum et adipisci eaque.","footer":"Assumenda cum molestias recusandae.","moreInfo":"Ad eos dicta ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
