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
      return {"slug":"quia-optio","name":"Quod et qui dolorem.","description":"Inventore culpa doloremque. Et consequuntur voluptas. Non sit dolorem.","price":80666.13,"header":"Et dicta sit nemo.","footer":"Qui molestiae soluta aut.","moreInfo":"Sit autem dolor vitae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
