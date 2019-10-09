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
      return {"slug":"quidem_natus","name":"Accusamus corrupti sed voluptatibus.","description":"Maxime delectus totam. Quisquam et quo. Laborum nesciunt eos.","price":17329.36,"header":"Qui consectetur necessitatibus corrupti.","footer":"Blanditiis mollitia recusandae ut.","moreInfo":"Alias ex impedit hic."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
