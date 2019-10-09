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
      return {"slug":"et_vero","name":"Distinctio et delectus illum.","description":"Eum ab qui. Vel dicta voluptatem. Ut eum quod.","price":34072.18,"header":"Aliquid cupiditate voluptas magnam.","footer":"Temporibus vero dolorem cupiditate.","moreInfo":"Voluptatibus qui rerum impedit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
