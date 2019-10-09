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
      return {"slug":"ut_nisi","name":"Et error tempore corporis.","description":"Quis provident nulla. Numquam aut sit. Amet voluptatem sit.","price":31753.74,"header":"Voluptas dolor temporibus cupiditate.","footer":"Qui eum itaque animi.","moreInfo":"Voluptas doloremque repellendus occaecati."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
