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
      return {"slug":"reprehenderit_aut","name":"Perspiciatis laudantium quis esse.","description":"Porro ut id. Assumenda non sit. Quos rerum voluptas.","price":44747.58,"header":"Perferendis eligendi corporis tempora.","footer":"Libero est odit est.","moreInfo":"Occaecati voluptas aspernatur quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
