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
      return {"slug":"voluptatum_eveniet","name":"Occaecati eum soluta exercitationem.","description":"Qui repellat autem. Aut expedita neque. Amet ullam non.","price":62935.72,"header":"Inventore non modi praesentium.","footer":"Veritatis suscipit deserunt nulla.","moreInfo":"Id in dolores perferendis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
