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
      return {"slug":"ad_et","name":"Eos occaecati tempore voluptas.","description":"Beatae est numquam. Minus est omnis. Sunt quo omnis.","price":16435.11,"header":"Quo quia non tempore.","footer":"Laboriosam laborum illum ut.","moreInfo":"Inventore iusto distinctio quis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
