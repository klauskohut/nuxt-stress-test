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
      return {"slug":"saepe_qui","name":"Eum consectetur et soluta.","description":"Quae ducimus cum. Sed accusamus voluptate. Eum doloremque omnis.","price":84676.31,"header":"Voluptas minus quisquam quia.","footer":"Cum architecto reiciendis tempore.","moreInfo":"Ab debitis aut libero."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
