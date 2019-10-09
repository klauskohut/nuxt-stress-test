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
      return {"slug":"quia-at","name":"Consectetur dolorem quo ipsa.","description":"Enim doloremque unde. Aspernatur nisi ut. Iste veritatis sint.","price":33086.02,"header":"Sit voluptas sed voluptatem.","footer":"Cum beatae aut tenetur.","moreInfo":"Aliquam sit et nemo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
