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
      return {"slug":"laborum_sed","name":"Aperiam qui quae nesciunt.","description":"Voluptatem in unde. Consequatur consequatur maxime. Delectus cum et.","price":94028.77,"header":"Ut recusandae earum eum.","footer":"Architecto molestiae aspernatur quam.","moreInfo":"Omnis quia dolores nemo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
