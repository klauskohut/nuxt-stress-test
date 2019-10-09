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
      return {"slug":"quaerat-mollitia","name":"Nihil ad et exercitationem.","description":"Fuga laborum minus. Eos impedit sit. Voluptas dignissimos doloremque.","price":48820.72,"header":"Aut quis accusamus consequuntur.","footer":"Libero quidem architecto excepturi.","moreInfo":"Labore ullam voluptatibus aliquid."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
