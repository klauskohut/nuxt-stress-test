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
      return {"slug":"harum-accusamus","name":"Debitis possimus ut facilis.","description":"Corporis iusto facere. Quod rerum sequi. Dolores eum porro.","price":16611.13,"header":"Labore ipsam optio blanditiis.","footer":"Numquam veritatis architecto est.","moreInfo":"Nihil unde aliquam voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
