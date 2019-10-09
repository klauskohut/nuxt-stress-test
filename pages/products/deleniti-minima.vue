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
      return {"slug":"deleniti-minima","name":"Neque adipisci praesentium perspiciatis.","description":"Velit vitae dolore. Sequi nesciunt et. Laudantium repellendus est.","price":52818.96,"header":"Nam distinctio quasi et.","footer":"Vel quaerat nesciunt quas.","moreInfo":"Ut quaerat voluptatem magnam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
