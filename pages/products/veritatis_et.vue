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
      return {"slug":"veritatis_et","name":"Dicta ratione nihil dolorem.","description":"Sit voluptatum qui. Dolores qui quasi. Aperiam facere voluptas.","price":25486.24,"header":"Saepe voluptates autem provident.","footer":"Sapiente dolorum omnis voluptas.","moreInfo":"Sunt quos accusantium adipisci."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
