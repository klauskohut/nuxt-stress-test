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
      return {"slug":"quo_facilis","name":"Quia ut libero eos.","description":"Voluptatem qui tempora. Ut fuga ut. Sit vel et.","price":97776.23,"header":"Corporis maiores sunt minima.","footer":"Sit vitae repellendus maxime.","moreInfo":"Consequatur explicabo fugiat quas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
