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
      return {"slug":"tempore_doloremque","name":"Repudiandae qui ut architecto.","description":"Error sed accusamus. Nobis sed sint. Est laudantium omnis.","price":12852.74,"header":"Est eligendi ut facere.","footer":"Enim aut rerum rem.","moreInfo":"Illum voluptas consequatur tempore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
