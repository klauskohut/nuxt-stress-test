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
      return {"slug":"laboriosam_quia","name":"Aut ipsam voluptas ex.","description":"Architecto in ut. Corporis saepe quos. Beatae distinctio omnis.","price":35327.65,"header":"Ea cupiditate officia impedit.","footer":"Quo eum sapiente harum.","moreInfo":"Atque illo hic aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
