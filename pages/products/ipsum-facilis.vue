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
      return {"slug":"ipsum-facilis","name":"Non aut sunt quia.","description":"Sit aperiam maiores. Sequi suscipit quibusdam. Ut minus laborum.","price":54023.06,"header":"Iste inventore distinctio sint.","footer":"Eum consequatur debitis sunt.","moreInfo":"Dignissimos libero reprehenderit doloribus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
