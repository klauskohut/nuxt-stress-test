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
      return {"slug":"voluptatem_modi","name":"Cumque voluptatem ipsam et.","description":"Est esse enim. Reprehenderit facilis debitis. Cumque facilis ex.","price":34215.85,"header":"Eligendi et est iure.","footer":"Et ab exercitationem repellat.","moreInfo":"Veritatis totam earum corrupti."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
