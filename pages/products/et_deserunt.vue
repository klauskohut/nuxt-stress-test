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
      return {"slug":"et_deserunt","name":"Ut molestiae iusto est.","description":"Dolorem iure consequuntur. Perspiciatis quo ipsam. Sed cupiditate voluptatem.","price":37145.98,"header":"Excepturi sed soluta autem.","footer":"Et perferendis molestiae adipisci.","moreInfo":"Modi est dolor aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
