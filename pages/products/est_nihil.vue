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
      return {"slug":"est_nihil","name":"Nihil quod fugit omnis.","description":"Sapiente voluptas consequatur. Consequuntur voluptas doloremque. Amet nesciunt eius.","price":97004.24,"header":"Qui non velit omnis.","footer":"Est et autem natus.","moreInfo":"Rerum dolorum perferendis velit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
