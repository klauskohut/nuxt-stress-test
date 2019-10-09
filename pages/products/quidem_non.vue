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
      return {"slug":"quidem_non","name":"Ab quia aliquam architecto.","description":"Cupiditate qui repellendus. Sed ipsa necessitatibus. Deleniti quasi quam.","price":15363.39,"header":"Fuga ratione nostrum nemo.","footer":"Odio accusantium modi adipisci.","moreInfo":"Animi sed quae iusto."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
