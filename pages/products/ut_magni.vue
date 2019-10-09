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
      return {"slug":"ut_magni","name":"Expedita numquam necessitatibus aut.","description":"Sequi magni consequatur. Reprehenderit distinctio porro. Molestiae error voluptas.","price":90393.95,"header":"Nesciunt ducimus error tempora.","footer":"Possimus non accusantium aspernatur.","moreInfo":"Inventore qui natus culpa."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
