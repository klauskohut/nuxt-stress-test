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
      return {"slug":"itaque_omnis","name":"Nihil sit quibusdam consequatur.","description":"Odio commodi ut. Sit modi fugiat. Velit mollitia suscipit.","price":62729.51,"header":"Dolorem nobis exercitationem ducimus.","footer":"Accusantium voluptas dignissimos qui.","moreInfo":"Cum quo qui est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
