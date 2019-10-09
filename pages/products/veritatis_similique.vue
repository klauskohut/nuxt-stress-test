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
      return {"slug":"veritatis_similique","name":"Quo sint qui ut.","description":"Neque quia voluptatem. Veniam consequuntur quia. Repellat illum fuga.","price":16844.63,"header":"Et assumenda eaque qui.","footer":"Vel accusamus eos veritatis.","moreInfo":"Aut adipisci et et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
