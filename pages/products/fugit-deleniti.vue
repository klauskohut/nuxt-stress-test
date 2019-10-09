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
      return {"slug":"fugit-deleniti","name":"Omnis eaque error minima.","description":"Illo dolorem perspiciatis. Voluptas error quos. Aliquam numquam dolorum.","price":81477.64,"header":"Aut consequatur dolores omnis.","footer":"Molestias unde hic iusto.","moreInfo":"Alias vero quidem fuga."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
