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
      return {"slug":"qui_quod","name":"Ut voluptates nihil quisquam.","description":"Magnam omnis fuga. Tempora aut libero. Ut incidunt ex.","price":99995.73,"header":"Et dolore voluptatibus sit.","footer":"Ex exercitationem fugiat sint.","moreInfo":"Rerum possimus quo rem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
