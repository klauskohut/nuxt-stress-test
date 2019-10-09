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
      return {"slug":"doloremque-quos","name":"Error aut reprehenderit adipisci.","description":"Quos aut nisi. Voluptatum minima distinctio. Omnis qui voluptates.","price":24470.29,"header":"Laborum laudantium optio qui.","footer":"Aperiam explicabo ut ut.","moreInfo":"Qui cumque vitae est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
