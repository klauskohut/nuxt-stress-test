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
      return {"slug":"enim_et","name":"Quia eaque qui delectus.","description":"Ut quisquam est. Voluptas velit voluptatem. Fuga minima velit.","price":76370.24,"header":"Est et est vitae.","footer":"Aut quisquam amet dolores.","moreInfo":"Omnis aliquam voluptas architecto."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
