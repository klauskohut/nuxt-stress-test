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
      return {"slug":"aut_sed","name":"Distinctio tempore aspernatur aut.","description":"Et quidem quisquam. Nobis inventore exercitationem. Est est cumque.","price":21808.41,"header":"Voluptatem dicta eveniet ratione.","footer":"Aut in totam magnam.","moreInfo":"Aliquid et iste nisi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
