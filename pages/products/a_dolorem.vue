<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <Slider />
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
      return {"slug":"a_dolorem","name":"Et numquam similique quis.","description":"Perferendis exercitationem atque. Est vel ut. Tempora vero eum.","price":38268.96,"header":"Error aut rem nihil.","footer":"Enim dolorem eum et.","moreInfo":"Magni qui ea qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
