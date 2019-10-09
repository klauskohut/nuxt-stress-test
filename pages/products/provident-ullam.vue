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
      return {"slug":"provident-ullam","name":"Nulla occaecati deserunt sit.","description":"Aspernatur deleniti error. Aut voluptas officia. Tempore quis nemo.","price":87902.78,"header":"Reiciendis aliquam mollitia quo.","footer":"Assumenda accusamus eos odio.","moreInfo":"Hic officiis neque eaque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
