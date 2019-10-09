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
      return {"slug":"modi_sed","name":"Aut in sit omnis.","description":"Provident consequatur quae. Voluptatibus vel perspiciatis. Officia et aut.","price":69925.51,"header":"Tempore et cumque fugiat.","footer":"Molestiae consequatur nisi amet.","moreInfo":"Eaque omnis et magni."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
