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
      return {"slug":"cupiditate_quidem","name":"Et qui commodi rem.","description":"Ut aperiam ullam. Cumque et expedita. Quaerat dicta itaque.","price":64621.15,"header":"Ad sed culpa laboriosam.","footer":"Similique sit id molestias.","moreInfo":"Nam qui quia voluptate."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
