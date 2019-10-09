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
      return {"slug":"sit-maxime","name":"Architecto id non maxime.","description":"Ad voluptas consequatur. Incidunt qui eum. Iste praesentium distinctio.","price":72537.74,"header":"Ut impedit nihil aliquam.","footer":"Autem est sed est.","moreInfo":"Dolores fugiat rerum non."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
