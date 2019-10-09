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
      return {"slug":"rerum-sit","name":"Reiciendis qui veniam voluptate.","description":"Quam ipsa aut. Ut repudiandae voluptatum. Nostrum occaecati dolorem.","price":14419.73,"header":"Magnam expedita doloribus repellat.","footer":"Vitae unde nihil recusandae.","moreInfo":"Iure et consequatur dicta."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
