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
      return {"slug":"eveniet-est","name":"Recusandae laboriosam autem doloremque.","description":"Ipsa aspernatur nihil. Sit laudantium fugit. Totam dolor aut.","price":63890.02,"header":"Adipisci debitis nisi tenetur.","footer":"Voluptatem consequatur voluptates dicta.","moreInfo":"Occaecati facere fugiat minus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
