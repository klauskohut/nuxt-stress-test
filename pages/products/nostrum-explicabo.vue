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
      return {"slug":"nostrum-explicabo","name":"Inventore beatae eaque repellat.","description":"Saepe totam rerum. Deserunt fugiat voluptatem. Doloremque autem asperiores.","price":54568.61,"header":"Soluta vero explicabo possimus.","footer":"Et corrupti temporibus sunt.","moreInfo":"Aspernatur asperiores repellendus rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
