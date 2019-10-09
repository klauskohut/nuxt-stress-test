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
      return {"slug":"consectetur-tempore","name":"Pariatur minus est enim.","description":"Possimus saepe aut. Nam est perferendis. Animi quisquam officiis.","price":72736.83,"header":"Non blanditiis aliquid odio.","footer":"Aut rerum iusto rerum.","moreInfo":"Rerum dicta illo ad."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
