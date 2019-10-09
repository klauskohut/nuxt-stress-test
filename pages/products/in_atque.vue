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
      return {"slug":"in_atque","name":"Rem reprehenderit ut id.","description":"Odio mollitia eligendi. Aspernatur impedit porro. Sapiente eos error.","price":18663.26,"header":"Iusto qui vero sed.","footer":"Rem possimus numquam sunt.","moreInfo":"Voluptatem aliquid soluta sunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
