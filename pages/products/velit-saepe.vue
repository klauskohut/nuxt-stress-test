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
      return {"slug":"velit-saepe","name":"Perspiciatis ab quis est.","description":"Deleniti facere asperiores. Aut natus sit. Quae atque omnis.","price":87678.71,"header":"Dolorem corporis dolores veniam.","footer":"Beatae velit et aut.","moreInfo":"Aspernatur dolor libero modi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
