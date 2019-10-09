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
      return {"slug":"deserunt_hic","name":"Quis non dolorem laborum.","description":"Repellendus enim illo. Nam qui non. Vel rerum dolor.","price":13329.95,"header":"Nostrum ut sapiente voluptas.","footer":"Praesentium eum autem et.","moreInfo":"Animi ut voluptatum rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
