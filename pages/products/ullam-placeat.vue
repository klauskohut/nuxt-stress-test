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
      return {"slug":"ullam-placeat","name":"Alias aut commodi dolorem.","description":"Ducimus aperiam aut. Fuga consectetur in. Non nesciunt inventore.","price":34679.48,"header":"Quibusdam cupiditate ea culpa.","footer":"Sit rerum explicabo saepe.","moreInfo":"Voluptas alias aspernatur ullam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
