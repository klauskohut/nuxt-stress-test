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
      return {"slug":"inventore_rem","name":"Adipisci possimus non enim.","description":"Sit quia ex. Minima sit nemo. Tempore debitis eos.","price":52420.57,"header":"Et aut non dolor.","footer":"Molestiae consectetur sequi error.","moreInfo":"Est similique dicta a."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
