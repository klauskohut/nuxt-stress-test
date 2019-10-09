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
      return {"slug":"voluptatem_sed","name":"Placeat saepe eum quis.","description":"Tempore consequatur facere. Hic ut omnis. Laborum et mollitia.","price":13216.45,"header":"Asperiores molestiae id harum.","footer":"Et dicta sapiente ex.","moreInfo":"Laudantium iusto non earum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
