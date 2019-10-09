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
      return {"slug":"ut-doloremque","name":"Ut sed deleniti laboriosam.","description":"Rerum rem nulla. Sequi aut tempora. Et perferendis omnis.","price":78095.83,"header":"Veniam cupiditate maiores illum.","footer":"Nihil repellendus suscipit fuga.","moreInfo":"Autem nulla itaque ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
