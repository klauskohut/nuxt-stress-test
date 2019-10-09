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
      return {"slug":"eos-nulla","name":"Quis non inventore necessitatibus.","description":"Nesciunt quia voluptatibus. Nemo ea inventore. Enim qui ut.","price":72670.53,"header":"Natus commodi ut labore.","footer":"Facilis molestiae in eos.","moreInfo":"Sequi qui amet sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
