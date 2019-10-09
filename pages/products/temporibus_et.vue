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
      return {"slug":"temporibus_et","name":"Omnis et magnam voluptatem.","description":"Quos ullam illum. Sed quo ipsa. Dolorum enim tenetur.","price":63463.69,"header":"Totam vitae soluta laudantium.","footer":"Tempore aut dignissimos et.","moreInfo":"Ea quas quasi placeat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
