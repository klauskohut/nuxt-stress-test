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
      return {"slug":"minima_repellendus","name":"Fuga recusandae sit ut.","description":"Ut reiciendis esse. Repellendus quis et. Eveniet ut quod.","price":15430.14,"header":"Adipisci tempora mollitia omnis.","footer":"Ratione harum omnis quam.","moreInfo":"Exercitationem laborum ducimus voluptas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
