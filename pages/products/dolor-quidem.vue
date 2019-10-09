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
      return {"slug":"dolor-quidem","name":"Et sit soluta voluptatum.","description":"Dicta sunt officiis. Quidem quasi et. Quisquam sed voluptatem.","price":87376.78,"header":"Doloribus autem sed iste.","footer":"Ducimus quos esse quasi.","moreInfo":"Vitae laudantium reiciendis quo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
