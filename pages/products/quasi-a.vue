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
      return {"slug":"quasi-a","name":"Fugit delectus quis dolorum.","description":"Odit eos quod. Et tempora animi. Corporis non eveniet.","price":38011.61,"header":"Et neque rerum est.","footer":"Officia praesentium dicta dolorum.","moreInfo":"Est fuga ab id."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
