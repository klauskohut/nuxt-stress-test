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
      return {"slug":"qui-voluptates","name":"Ut voluptas voluptatem amet.","description":"Ab voluptate beatae. Voluptatibus laboriosam accusamus. A repellendus et.","price":24465.81,"header":"Mollitia est facere a.","footer":"Quasi est commodi dolore.","moreInfo":"Eligendi voluptate tempora doloremque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
