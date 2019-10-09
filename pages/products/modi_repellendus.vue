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
      return {"slug":"modi_repellendus","name":"Consequatur nam non dolor.","description":"Et officiis consequuntur. Cum sint dolor. Est et voluptatibus.","price":99113.12,"header":"Natus atque illo autem.","footer":"Quia odio eos asperiores.","moreInfo":"Ipsa reprehenderit facere eveniet."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
