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
      return {"slug":"voluptas_officiis","name":"Reprehenderit dignissimos omnis quae.","description":"Ipsum fuga qui. Et aut voluptatem. Rem voluptas inventore.","price":48068.54,"header":"Quis asperiores quia hic.","footer":"Quas omnis nesciunt quo.","moreInfo":"Maiores iure qui dolore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
