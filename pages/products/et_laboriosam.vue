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
      return {"slug":"et_laboriosam","name":"Enim omnis nihil ullam.","description":"Tenetur vero repellendus. Eveniet ea doloremque. Sint fuga laboriosam.","price":56689.57,"header":"Quo qui illo dolor.","footer":"Quae dolorem repellendus molestiae.","moreInfo":"Enim minus repudiandae nobis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
