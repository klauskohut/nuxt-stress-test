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
      return {"slug":"corrupti-qui","name":"Consequuntur sed ex eos.","description":"Aperiam ipsam molestiae. Earum odio fugiat. In nesciunt molestiae.","price":33650.19,"header":"Consequatur nesciunt assumenda qui.","footer":"Quo fugiat aspernatur commodi.","moreInfo":"Expedita at tempore itaque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
