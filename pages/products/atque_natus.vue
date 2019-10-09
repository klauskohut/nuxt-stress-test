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
      return {"slug":"atque_natus","name":"Labore consequatur ut quo.","description":"Et qui aut. Distinctio labore sit. In nulla veritatis.","price":66700.95,"header":"Nihil sit sit voluptatibus.","footer":"Est tempore eaque et.","moreInfo":"Voluptas est temporibus et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
