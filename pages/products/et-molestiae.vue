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
      return {"slug":"et-molestiae","name":"Natus in architecto quae.","description":"Repudiandae repellat laudantium. Soluta tempore omnis. Eaque facilis veritatis.","price":24742.62,"header":"Ut sed nisi qui.","footer":"Ut ad corporis amet.","moreInfo":"Et ipsum temporibus rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
