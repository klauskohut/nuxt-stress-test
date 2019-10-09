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
      return {"slug":"consequatur_earum","name":"Placeat aperiam blanditiis voluptas.","description":"Et iste doloribus. Dolorum facere esse. Quod natus dicta.","price":54243.32,"header":"Dolorem beatae omnis numquam.","footer":"Aliquid sit voluptatem enim.","moreInfo":"Sit itaque et molestiae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
