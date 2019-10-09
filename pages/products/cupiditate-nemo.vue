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
      return {"slug":"cupiditate-nemo","name":"Suscipit sequi cupiditate quia.","description":"Dolorum ducimus ad. Iste voluptatem a. Aut nisi velit.","price":50197.76,"header":"Repellendus et sunt doloribus.","footer":"Aut voluptate qui distinctio.","moreInfo":"Alias at ex tempora."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
