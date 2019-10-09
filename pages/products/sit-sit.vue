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
      return {"slug":"sit-sit","name":"Aut dolor quia modi.","description":"Perspiciatis ab consequuntur. Nesciunt deserunt autem. Voluptatem consequatur velit.","price":14754.62,"header":"Dolore unde placeat voluptatibus.","footer":"Sit velit repellendus reprehenderit.","moreInfo":"Suscipit ratione quos provident."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
