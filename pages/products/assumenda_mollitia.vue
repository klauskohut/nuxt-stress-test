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
      return {"slug":"assumenda_mollitia","name":"Nostrum consequuntur hic repudiandae.","description":"Accusamus harum id. Labore maxime quibusdam. Velit voluptas placeat.","price":51364.03,"header":"Aliquid modi qui recusandae.","footer":"Illum quis fugit distinctio.","moreInfo":"Molestias quasi quisquam quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
