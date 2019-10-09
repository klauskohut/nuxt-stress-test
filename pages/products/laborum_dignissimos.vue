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
      return {"slug":"laborum_dignissimos","name":"In rerum quod est.","description":"Impedit aut natus. Nemo sit sed. Eius aperiam quia.","price":50401.19,"header":"In neque molestiae optio.","footer":"Aut voluptas aut qui.","moreInfo":"Ipsam commodi inventore ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
