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
      return {"slug":"libero-in","name":"Sint quia commodi nulla.","description":"Labore at quo. Dicta officiis atque. Non a occaecati.","price":96209.71,"header":"Exercitationem omnis nihil ea.","footer":"Quia mollitia fugiat repellat.","moreInfo":"Iusto aspernatur saepe sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
