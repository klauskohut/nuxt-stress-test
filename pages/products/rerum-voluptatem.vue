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
      return {"slug":"rerum-voluptatem","name":"Eos ipsa voluptatum tempore.","description":"Beatae ut eius. Ipsum qui fuga. Reprehenderit non a.","price":96258.56,"header":"Tempora pariatur cumque est.","footer":"Rerum a voluptatem quo.","moreInfo":"Natus voluptatem perferendis et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
