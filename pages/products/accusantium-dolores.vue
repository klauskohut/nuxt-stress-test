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
      return {"slug":"accusantium-dolores","name":"Laborum nemo aliquam in.","description":"Atque eligendi est. Alias velit in. Minus vitae temporibus.","price":16686.04,"header":"Officia architecto quia ab.","footer":"Et consequuntur ut amet.","moreInfo":"Et vel a qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
