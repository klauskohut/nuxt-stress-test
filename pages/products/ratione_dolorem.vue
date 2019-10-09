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
      return {"slug":"ratione_dolorem","name":"Ipsum soluta molestiae quod.","description":"Aspernatur voluptas repellendus. Fugiat iusto explicabo. Qui iure ut.","price":83031.23,"header":"Mollitia odit distinctio non.","footer":"Atque ut magnam suscipit.","moreInfo":"Quia nemo neque et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
