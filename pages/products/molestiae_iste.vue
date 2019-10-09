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
      return {"slug":"molestiae_iste","name":"Eaque ut repellendus fugiat.","description":"Consectetur sint qui. Officiis voluptas odio. Id fugiat quos.","price":93663.11,"header":"Ut nihil dolore nesciunt.","footer":"Veritatis vero quia sed.","moreInfo":"Voluptas incidunt adipisci fugit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
