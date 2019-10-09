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
      return {"slug":"necessitatibus_sint","name":"Sed inventore aut laudantium.","description":"Dolores soluta earum. Ut perspiciatis dignissimos. Iure quibusdam et.","price":44441.96,"header":"Similique in rem voluptates.","footer":"Quam rerum necessitatibus ratione.","moreInfo":"Esse aut accusamus dignissimos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
