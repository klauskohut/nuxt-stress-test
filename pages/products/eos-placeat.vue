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
      return {"slug":"eos-placeat","name":"Iure nisi iusto nihil.","description":"Qui illo sed. Incidunt deleniti delectus. Fugit est accusantium.","price":79030.31,"header":"Illum soluta sunt quae.","footer":"Rerum doloribus quia vel.","moreInfo":"Eveniet modi nihil alias."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
