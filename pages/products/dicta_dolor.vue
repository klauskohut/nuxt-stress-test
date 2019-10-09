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
      return {"slug":"dicta_dolor","name":"Quis sed illo ex.","description":"Aspernatur at deserunt. Sint excepturi quo. Nostrum non repellendus.","price":93135.28,"header":"Aut sit esse culpa.","footer":"Nemo natus quis et.","moreInfo":"Corrupti quaerat sit numquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
