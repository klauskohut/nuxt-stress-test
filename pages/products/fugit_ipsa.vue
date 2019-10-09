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
      return {"slug":"fugit_ipsa","name":"Repudiandae harum numquam magni.","description":"Aut sunt quia. Unde officiis delectus. Est et non.","price":33285.45,"header":"Tempore numquam nihil voluptatem.","footer":"Aliquid ea ipsum voluptatibus.","moreInfo":"Explicabo praesentium sunt labore."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
