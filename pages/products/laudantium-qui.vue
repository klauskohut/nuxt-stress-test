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
      return {"slug":"laudantium-qui","name":"Provident molestias molestiae ab.","description":"Optio voluptatibus et. Accusamus doloribus corporis. Beatae animi neque.","price":20278.26,"header":"Unde dicta rerum sit.","footer":"Ut enim quo omnis.","moreInfo":"Ut quod eveniet culpa."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
