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
      return {"slug":"doloremque_placeat","name":"Quam velit eaque voluptatum.","description":"Qui doloribus ad. Rerum ullam assumenda. Qui maiores repellendus.","price":89121.87,"header":"Veritatis itaque voluptas ut.","footer":"Quidem nemo repellendus omnis.","moreInfo":"Magni tempora omnis temporibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
