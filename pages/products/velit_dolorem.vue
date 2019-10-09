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
      return {"slug":"velit_dolorem","name":"Eum voluptatem quo totam.","description":"Quia omnis et. Minus totam quia. Architecto optio ullam.","price":61723.13,"header":"Hic aperiam ut quia.","footer":"Enim iusto possimus et.","moreInfo":"Iusto expedita iure beatae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
