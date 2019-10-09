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
      return {"slug":"adipisci_et","name":"Sed blanditiis illum ut.","description":"Tempora pariatur perspiciatis. Sit aut dolorum. Ab voluptas incidunt.","price":35134.28,"header":"Soluta enim exercitationem consequatur.","footer":"Nihil quibusdam similique sunt.","moreInfo":"Ipsa minima debitis dolor."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
