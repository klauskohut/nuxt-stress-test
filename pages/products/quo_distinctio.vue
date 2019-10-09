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
      return {"slug":"quo_distinctio","name":"Quasi non sit vel.","description":"Facilis consequatur dignissimos. Itaque quibusdam nostrum. Doloremque rerum voluptates.","price":60318.29,"header":"Exercitationem commodi molestiae beatae.","footer":"Assumenda sequi qui qui.","moreInfo":"Cupiditate quia voluptatibus unde."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
