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
      return {"slug":"voluptatibus_voluptas","name":"Incidunt repellat rerum qui.","description":"Quisquam aliquam omnis. Voluptatem iure dicta. Eos accusantium rerum.","price":85858.34,"header":"Accusamus sed hic adipisci.","footer":"Asperiores placeat omnis itaque.","moreInfo":"Et optio praesentium rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
