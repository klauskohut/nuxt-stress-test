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
      return {"slug":"autem-velit","name":"Rerum voluptatem eos in.","description":"Nobis sit tenetur. Sequi cum ratione. Dolorem debitis quos.","price":81966.07,"header":"Ab ipsum ad eum.","footer":"Eos omnis voluptatem doloribus.","moreInfo":"Ea pariatur eum voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
