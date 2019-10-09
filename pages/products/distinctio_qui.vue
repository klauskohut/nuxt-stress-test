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
      return {"slug":"distinctio_qui","name":"Aliquid cumque perferendis hic.","description":"Veritatis perspiciatis modi. Omnis voluptas cum. Dicta eius et.","price":31367.96,"header":"Commodi vel exercitationem modi.","footer":"Aut qui quis omnis.","moreInfo":"Temporibus quia maxime exercitationem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
