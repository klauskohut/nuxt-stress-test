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
      return {"slug":"quia_voluptates","name":"Autem commodi consequatur aut.","description":"Omnis iste occaecati. Qui dicta velit. Magni repellat perferendis.","price":50294.78,"header":"Rerum est praesentium facilis.","footer":"Explicabo aut magni debitis.","moreInfo":"Similique et dolorum et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
