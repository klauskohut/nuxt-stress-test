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
      return {"slug":"aspernatur-est","name":"Necessitatibus consequuntur voluptatibus saepe.","description":"Non ex voluptatem. Ut architecto quo. Ducimus maiores dolores.","price":89715.58,"header":"Rerum in porro corrupti.","footer":"Et et esse sit.","moreInfo":"Quia odio blanditiis neque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
