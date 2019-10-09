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
      return {"slug":"ea_ab","name":"Maiores aut et quo.","description":"Sit quas harum. Ut repellat veritatis. Voluptas sit consectetur.","price":41254.11,"header":"Fuga quia repudiandae nam.","footer":"Eos est numquam eum.","moreInfo":"Aut iste tenetur odio."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
