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
      return {"slug":"corporis_in","name":"Voluptates inventore quidem a.","description":"Ab vel dolores. Cupiditate est consequatur. Laboriosam illum voluptatem.","price":59970.99,"header":"Et officiis quisquam rem.","footer":"Molestiae asperiores quia deleniti.","moreInfo":"Commodi voluptatum est voluptatem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
