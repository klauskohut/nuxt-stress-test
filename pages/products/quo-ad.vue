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
      return {"slug":"quo-ad","name":"Earum aliquid enim qui.","description":"Qui expedita aliquid. Ipsum tenetur sed. Porro aut repellendus.","price":22872.92,"header":"Enim aut itaque ea.","footer":"Doloremque aliquid rerum voluptas.","moreInfo":"Porro aut tempore ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
