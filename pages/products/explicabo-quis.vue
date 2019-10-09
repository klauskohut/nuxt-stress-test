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
      return {"slug":"explicabo-quis","name":"Ducimus quibusdam et quae.","description":"Ut laborum voluptatem. Sunt qui consequuntur. Eveniet quo repellat.","price":74468.74,"header":"Aut id voluptatibus totam.","footer":"Vel veniam a velit.","moreInfo":"Nobis consequuntur eius qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
