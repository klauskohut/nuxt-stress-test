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
      return {"slug":"vel-minus","name":"Excepturi repudiandae cupiditate rerum.","description":"Consequuntur soluta harum. Nam facilis eum. Tempore aperiam dolor.","price":11775.82,"header":"Nulla culpa consequuntur sit.","footer":"Dolor et ipsam cum.","moreInfo":"Tempore unde alias nihil."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
