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
      return {"slug":"temporibus_tenetur","name":"Sit officiis autem commodi.","description":"Sequi voluptatem dolorem. Atque architecto et. Sunt nemo est.","price":56699.96,"header":"Maxime quam asperiores amet.","footer":"Aliquid maxime sapiente hic.","moreInfo":"Ipsum rerum voluptates alias."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
