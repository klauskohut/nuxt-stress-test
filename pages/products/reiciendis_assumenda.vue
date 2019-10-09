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
      return {"slug":"reiciendis_assumenda","name":"Hic qui enim tempora.","description":"Ea esse est. Aspernatur dolores iure. Est ullam sed.","price":71821.53,"header":"Perferendis minus voluptas dolore.","footer":"Et quasi perspiciatis iste.","moreInfo":"Autem modi blanditiis magni."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
