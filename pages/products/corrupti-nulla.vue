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
      return {"slug":"corrupti-nulla","name":"Recusandae vel consectetur quia.","description":"Ex voluptatem quam. Animi incidunt sequi. Optio ad voluptatibus.","price":39355.96,"header":"Ipsa ut quam maiores.","footer":"Ea consequatur voluptas eius.","moreInfo":"Cum consequuntur corporis sit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
