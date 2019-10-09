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
      return {"slug":"laborum_voluptatem","name":"Sit illum nostrum sit.","description":"Delectus perspiciatis at. Et placeat unde. Enim corrupti officia.","price":10269.25,"header":"Consequatur libero quasi ut.","footer":"Deleniti fugiat optio est.","moreInfo":"Dolor labore repellat laudantium."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
