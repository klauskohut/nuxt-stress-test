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
      return {"slug":"at_inventore","name":"Animi quis odio sed.","description":"Neque esse unde. Quia iure qui. Quisquam quaerat in.","price":75013.57,"header":"Rem qui ut eos.","footer":"Vero omnis quas reiciendis.","moreInfo":"Voluptates error consequatur placeat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
