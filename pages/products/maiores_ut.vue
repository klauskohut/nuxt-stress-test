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
      return {"slug":"maiores_ut","name":"Distinctio cupiditate exercitationem quia.","description":"Labore rerum ut. Rerum non similique. Aut quod ex.","price":20715.64,"header":"Sunt est ab at.","footer":"Delectus nihil molestiae voluptate.","moreInfo":"Amet error enim commodi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
