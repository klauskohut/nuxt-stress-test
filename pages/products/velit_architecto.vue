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
      return {"slug":"velit_architecto","name":"Eum tempora sapiente est.","description":"Nulla voluptates nostrum. At voluptate veritatis. Architecto praesentium ipsam.","price":49925.22,"header":"Exercitationem rem qui recusandae.","footer":"Nobis error quidem nam.","moreInfo":"Id doloribus reiciendis animi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
