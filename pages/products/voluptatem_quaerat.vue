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
      return {"slug":"voluptatem_quaerat","name":"Provident sit et voluptatum.","description":"Aut enim laudantium. Iste quaerat voluptatum. Et tenetur repellat.","price":59597.46,"header":"Sit sed neque dignissimos.","footer":"Odit totam et itaque.","moreInfo":"Placeat aspernatur itaque et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
