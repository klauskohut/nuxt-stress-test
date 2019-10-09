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
      return {"slug":"omnis_ut","name":"Voluptatem sit numquam enim.","description":"Inventore ea assumenda. Optio est soluta. Qui sint deleniti.","price":60053.87,"header":"Animi vero mollitia sint.","footer":"Voluptas qui esse corrupti.","moreInfo":"Doloremque est nam cupiditate."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
