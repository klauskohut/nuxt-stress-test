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
      return {"slug":"ad_est","name":"Sit libero possimus et.","description":"Laborum et dolorum. Rerum consequatur rerum. Et nostrum a.","price":26443.62,"header":"Modi autem nostrum facere.","footer":"Id perspiciatis blanditiis amet.","moreInfo":"Doloribus eos minus magnam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
