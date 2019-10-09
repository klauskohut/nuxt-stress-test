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
      return {"slug":"ut-dolore","name":"Cum eaque non deserunt.","description":"Accusamus beatae sed. Minima itaque consequatur. Dolorum sequi inventore.","price":31901.14,"header":"Alias deleniti aliquid et.","footer":"Molestias nam minima est.","moreInfo":"Est id voluptatem provident."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
