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
      return {"slug":"explicabo-et","name":"Omnis eligendi minus tempora.","description":"Maxime delectus repellat. Et omnis est. Et quia dignissimos.","price":48439.65,"header":"Sunt tempora vitae saepe.","footer":"Velit odio magnam exercitationem.","moreInfo":"Blanditiis saepe porro voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
