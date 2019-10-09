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
      return {"slug":"et-esse","name":"Neque dolorum dignissimos sint.","description":"Rem provident quo. Iusto quas eos. Aliquid tempore ut.","price":13972.76,"header":"Accusamus minus sint sed.","footer":"Corrupti in est magnam.","moreInfo":"Nihil qui dignissimos officia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
