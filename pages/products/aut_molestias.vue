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
      return {"slug":"aut_molestias","name":"Atque voluptatem et commodi.","description":"Modi occaecati unde. Error incidunt saepe. Dolorem cumque perspiciatis.","price":46811.79,"header":"Dolor eveniet aut dolores.","footer":"Aliquid reiciendis ea dolores.","moreInfo":"Provident qui nihil expedita."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
