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
      return {"slug":"sit-qui","name":"Quisquam nostrum rerum harum.","description":"Modi qui quo. Molestias perferendis quia. Vel perferendis voluptatem.","price":36146.97,"header":"Sed fuga velit sunt.","footer":"Reprehenderit minus illum optio.","moreInfo":"Est laudantium id et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
