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
      return {"slug":"sint-excepturi","name":"Modi distinctio voluptatem illum.","description":"Distinctio et est. Dolore quas eum. Aut necessitatibus asperiores.","price":79352.07,"header":"Quo velit dolores quod.","footer":"Facere vitae vel accusamus.","moreInfo":"Voluptatem beatae ea est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
