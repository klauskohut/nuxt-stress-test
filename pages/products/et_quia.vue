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
      return {"slug":"et_quia","name":"Perferendis vel aut magnam.","description":"Accusamus dignissimos excepturi. Ipsa incidunt quo. Eos ad vel.","price":81766.63,"header":"Ipsum quo nihil quia.","footer":"Dolorum eum nulla beatae.","moreInfo":"Est amet saepe deserunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
