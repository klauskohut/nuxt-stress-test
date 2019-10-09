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
      return {"slug":"culpa_sed","name":"Rem et ipsam et.","description":"Aspernatur repellendus odit. Dignissimos excepturi rerum. Rerum placeat quibusdam.","price":89176.66,"header":"Voluptatem quisquam nihil quos.","footer":"Atque expedita natus aut.","moreInfo":"Distinctio rerum aut tempore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
