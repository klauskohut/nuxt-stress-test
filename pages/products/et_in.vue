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
      return {"slug":"et_in","name":"Hic veritatis cum similique.","description":"Dolorem aut amet. Suscipit debitis voluptas. Iusto voluptas ullam.","price":53013.13,"header":"Veniam itaque et iusto.","footer":"Repudiandae alias laudantium fugiat.","moreInfo":"Nulla hic molestias consequatur."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
