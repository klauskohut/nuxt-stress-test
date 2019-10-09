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
      return {"slug":"libero_ipsum","name":"Omnis sit at eligendi.","description":"Et commodi eum. Incidunt expedita ut. Earum alias voluptas.","price":94490.83,"header":"Omnis eligendi qui commodi.","footer":"Ut eligendi consequatur autem.","moreInfo":"Quia molestiae quisquam aliquid."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
