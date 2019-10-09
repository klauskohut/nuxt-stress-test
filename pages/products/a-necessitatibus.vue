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
      return {"slug":"a-necessitatibus","name":"Odit quae iure quod.","description":"Voluptatum nisi at. Autem et deleniti. Ex voluptas a.","price":32177.28,"header":"Ut repellendus id repellat.","footer":"Placeat id voluptas autem.","moreInfo":"Dolores aliquid omnis repellat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
