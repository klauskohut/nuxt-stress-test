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
      return {"slug":"fugiat_placeat","name":"Excepturi voluptas qui rerum.","description":"Enim enim officiis. Dolorum et sit. Tempore numquam non.","price":36161.51,"header":"Assumenda necessitatibus earum eum.","footer":"Atque vitae occaecati architecto.","moreInfo":"Et temporibus qui maxime."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
