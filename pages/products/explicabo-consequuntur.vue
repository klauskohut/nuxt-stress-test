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
      return {"slug":"explicabo-consequuntur","name":"Et voluptate error iure.","description":"Esse odio fuga. Beatae aut aliquam. Velit aut sit.","price":44747.23,"header":"Dolores non magnam quisquam.","footer":"Soluta quia doloremque id.","moreInfo":"Amet repudiandae eum optio."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
