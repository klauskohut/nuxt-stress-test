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
      return {"slug":"est_illum","name":"Quam maiores aperiam atque.","description":"Et sequi doloribus. Non vel eligendi. Commodi qui fugiat.","price":54047.46,"header":"Et quo modi saepe.","footer":"Laboriosam in consequatur quos.","moreInfo":"Reiciendis sapiente dolorum et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
