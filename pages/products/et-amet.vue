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
      return {"slug":"et-amet","name":"Aspernatur ducimus eum ut.","description":"In nostrum sapiente. Aliquam dolorem earum. Libero quibusdam facilis.","price":28591.96,"header":"Totam optio eum dolorem.","footer":"Eaque dignissimos et non.","moreInfo":"Ut saepe voluptas mollitia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
