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
      return {"slug":"voluptas-asperiores","name":"Magni voluptatem quia sit.","description":"Commodi porro amet. Quas blanditiis reprehenderit. Non quia molestias.","price":65119.47,"header":"Nihil sapiente iure assumenda.","footer":"Tenetur iste reprehenderit quos.","moreInfo":"Temporibus aliquam a fugiat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
