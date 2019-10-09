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
      return {"slug":"modi-facere","name":"Aut praesentium deserunt non.","description":"Praesentium et aperiam. Numquam excepturi deleniti. Qui exercitationem ipsa.","price":55817.24,"header":"Autem accusamus dolores ut.","footer":"Dolor consectetur fuga eius.","moreInfo":"Et nihil neque hic."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
