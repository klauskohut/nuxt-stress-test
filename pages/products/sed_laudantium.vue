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
      return {"slug":"sed_laudantium","name":"Eius voluptas magnam recusandae.","description":"Ut non ad. Dolorem libero incidunt. Et accusantium quia.","price":26402.45,"header":"Nihil earum doloribus autem.","footer":"Sint modi ut illum.","moreInfo":"Dolor et quibusdam nihil."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
