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
      return {"slug":"optio-nisi","name":"Eligendi facilis ipsa doloremque.","description":"Vel et sed. Consectetur eius unde. Autem voluptatem similique.","price":32396.26,"header":"Ea ad nobis asperiores.","footer":"Ullam et voluptatem sit.","moreInfo":"Rem nihil sit soluta."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
