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
      return {"slug":"aut_delectus","name":"Deserunt et corrupti rerum.","description":"Cupiditate esse nam. A dignissimos officiis. Quisquam in inventore.","price":65469.16,"header":"Ut ducimus veritatis omnis.","footer":"Sed quibusdam vitae dolorem.","moreInfo":"Quibusdam eos consequatur repellat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
