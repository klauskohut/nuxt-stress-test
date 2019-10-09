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
      return {"slug":"et-optio","name":"Quo est velit modi.","description":"Provident dolor est. Nesciunt est et. Id aspernatur praesentium.","price":87844.42,"header":"Doloremque quis tempora alias.","footer":"Nisi aut maiores voluptatem.","moreInfo":"Dolor sint harum mollitia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
