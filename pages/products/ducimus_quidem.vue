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
      return {"slug":"ducimus_quidem","name":"Mollitia ex fuga enim.","description":"Neque expedita suscipit. Ut non unde. Soluta temporibus blanditiis.","price":59405.52,"header":"Blanditiis tempore voluptates eos.","footer":"Sit perspiciatis officiis et.","moreInfo":"Omnis quidem et et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
