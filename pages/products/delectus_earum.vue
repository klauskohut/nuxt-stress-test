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
      return {"slug":"delectus_earum","name":"Iure eligendi vitae est.","description":"Molestiae excepturi odio. Fuga deleniti suscipit. Totam enim ducimus.","price":44401.08,"header":"Est deleniti iste ut.","footer":"Delectus voluptate ipsam et.","moreInfo":"Molestiae et aperiam praesentium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
