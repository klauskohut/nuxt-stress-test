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
      return {"slug":"delectus_quidem","name":"Eveniet iusto aut deleniti.","description":"Magnam necessitatibus sit. Vero eligendi doloremque. Aut sed placeat.","price":90327.76,"header":"Aut rerum qui id.","footer":"Sint ducimus incidunt exercitationem.","moreInfo":"Aliquam cupiditate occaecati eius."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
