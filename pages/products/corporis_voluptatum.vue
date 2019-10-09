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
      return {"slug":"corporis_voluptatum","name":"Ut est quasi nihil.","description":"Perferendis molestiae atque. In quis blanditiis. Ipsa autem delectus.","price":29276.73,"header":"In ut magnam qui.","footer":"Ducimus excepturi aut ad.","moreInfo":"Facere deleniti quo vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
