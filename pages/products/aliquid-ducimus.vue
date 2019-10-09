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
      return {"slug":"aliquid-ducimus","name":"Est harum error deleniti.","description":"Nemo deserunt accusantium. Sequi dolores in. Voluptas nihil sint.","price":48446.47,"header":"Fugit eos fugiat beatae.","footer":"Necessitatibus soluta ipsam magni.","moreInfo":"Enim iste deserunt eaque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
