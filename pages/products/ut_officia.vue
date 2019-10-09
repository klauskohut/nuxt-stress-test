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
      return {"slug":"ut_officia","name":"Optio error voluptate totam.","description":"Adipisci asperiores porro. Est est porro. Doloribus odit vel.","price":40633.43,"header":"Ipsum reprehenderit sint consectetur.","footer":"Nemo perspiciatis et vel.","moreInfo":"Eligendi qui amet dolorem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
