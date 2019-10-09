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
      return {"slug":"libero-eveniet","name":"Occaecati autem vel ullam.","description":"Fugiat voluptates dicta. Quidem quo aut. Et ut dolorem.","price":99674.79,"header":"Excepturi ut sint ut.","footer":"Dolorem placeat occaecati aut.","moreInfo":"Ex ut eos eum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
