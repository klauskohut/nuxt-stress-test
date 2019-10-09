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
      return {"slug":"nemo-facilis","name":"Quas vero in sint.","description":"Ducimus ab illo. Omnis amet totam. Minus dolores corporis.","price":60173.04,"header":"Perferendis quia ipsum velit.","footer":"In dicta et quibusdam.","moreInfo":"Accusantium ea vel ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
