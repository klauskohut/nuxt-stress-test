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
      return {"slug":"odio_architecto","name":"Hic nesciunt et quam.","description":"Assumenda facilis expedita. Assumenda rerum voluptates. Quo doloremque totam.","price":24756.45,"header":"Ut enim quia accusantium.","footer":"Incidunt rem molestiae dicta.","moreInfo":"Non et aut natus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
