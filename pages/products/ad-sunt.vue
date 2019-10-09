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
      return {"slug":"ad-sunt","name":"Perferendis magni voluptatem ad.","description":"Ad molestiae accusamus. Minima ratione iste. Facere praesentium et.","price":43331.44,"header":"Sit dolorem commodi laudantium.","footer":"Soluta qui distinctio minus.","moreInfo":"Deserunt et ea enim."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
