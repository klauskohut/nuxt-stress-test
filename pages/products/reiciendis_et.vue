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
      return {"slug":"reiciendis_et","name":"Illo unde numquam velit.","description":"Expedita molestiae est. Et quis maiores. Corrupti quaerat rerum.","price":23854.61,"header":"Sed voluptas id alias.","footer":"Voluptas dolorem rem temporibus.","moreInfo":"Deserunt quia perspiciatis voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
