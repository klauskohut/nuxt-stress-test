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
      return {"slug":"rerum-vero","name":"Unde modi quia illum.","description":"Ipsam temporibus eos. Qui repudiandae itaque. Officiis ut non.","price":76365.04,"header":"Minima qui totam vel.","footer":"Enim quod dignissimos numquam.","moreInfo":"Aut nesciunt sint quos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
