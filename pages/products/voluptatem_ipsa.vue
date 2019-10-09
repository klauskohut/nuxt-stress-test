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
      return {"slug":"voluptatem_ipsa","name":"Tempora ex fuga id.","description":"Ipsum facere esse. Aliquid aut provident. Excepturi ut ratione.","price":87296.81,"header":"Sit reiciendis quae ipsa.","footer":"Enim aut consequuntur eaque.","moreInfo":"Beatae laudantium molestiae delectus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
