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
      return {"slug":"quod_ab","name":"Ut et veniam voluptatibus.","description":"Optio non est. Rerum ipsam tempore. Vel eveniet et.","price":23909.19,"header":"Vitae vel veritatis a.","footer":"Odio doloremque tempora sit.","moreInfo":"Vero sunt aliquam similique."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
