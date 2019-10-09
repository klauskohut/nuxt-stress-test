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
      return {"slug":"et_fugit","name":"Ea aspernatur facere veritatis.","description":"Quis numquam possimus. Harum voluptatum mollitia. Dolorem ad dolor.","price":86675.88,"header":"Quaerat quis autem occaecati.","footer":"Modi nam distinctio exercitationem.","moreInfo":"Numquam et ipsa error."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
