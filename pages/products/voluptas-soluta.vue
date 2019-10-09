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
      return {"slug":"voluptas-soluta","name":"Ipsa aut occaecati qui.","description":"Quia sapiente est. Distinctio a aut. Sint exercitationem distinctio.","price":11148.78,"header":"Eius eveniet architecto exercitationem.","footer":"Dolores aut ex cumque.","moreInfo":"Quas hic omnis soluta."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
