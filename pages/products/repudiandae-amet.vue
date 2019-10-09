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
      return {"slug":"repudiandae-amet","name":"Quo omnis praesentium mollitia.","description":"Hic unde natus. Nam enim voluptatum. Aliquam dolores sunt.","price":21163.64,"header":"Nulla praesentium officiis accusamus.","footer":"Quia quo architecto dicta.","moreInfo":"Consequatur voluptas alias provident."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
