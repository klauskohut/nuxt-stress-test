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
      return {"slug":"earum_repellendus","name":"Doloribus suscipit inventore laudantium.","description":"Dolores et voluptatem. Sint quia id. Sit et reprehenderit.","price":78638.55,"header":"Quia dolore est culpa.","footer":"Doloremque dolor debitis in.","moreInfo":"Corrupti dolore aperiam ipsa."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
