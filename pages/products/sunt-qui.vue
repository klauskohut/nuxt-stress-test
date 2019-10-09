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
      return {"slug":"sunt-qui","name":"Consectetur sint soluta praesentium.","description":"Ut dolore occaecati. Ea possimus in. Aliquam repellendus eligendi.","price":37474.46,"header":"Laboriosam voluptatem sequi inventore.","footer":"Esse ut est iusto.","moreInfo":"Est est soluta facilis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
