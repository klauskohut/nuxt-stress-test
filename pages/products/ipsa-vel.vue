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
      return {"slug":"ipsa-vel","name":"Tempore ut exercitationem facere.","description":"Quo est alias. Ex ipsam officia. Vitae totam tempora.","price":17040.38,"header":"Quasi molestiae dolor qui.","footer":"Dignissimos necessitatibus fugit id.","moreInfo":"Omnis illum consequatur quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
