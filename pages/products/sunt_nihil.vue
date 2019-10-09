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
      return {"slug":"sunt_nihil","name":"Cum ea voluptatem hic.","description":"Dolorem nemo ab. Debitis unde velit. Rem possimus vitae.","price":38800.49,"header":"Esse quam cupiditate dolorem.","footer":"Enim dolore fugiat magnam.","moreInfo":"Odit eaque sunt cupiditate."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
