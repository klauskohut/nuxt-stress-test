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
      return {"slug":"aliquam_molestiae","name":"Modi doloribus magnam enim.","description":"Ipsa et ut. Totam voluptate qui. Ut ex nulla.","price":99118.95,"header":"Dolorem quisquam quibusdam qui.","footer":"Dolorem officiis aut voluptatem.","moreInfo":"Tenetur alias molestiae dolores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
