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
      return {"slug":"occaecati_ut","name":"Officiis nihil iusto ullam.","description":"Recusandae totam ad. Qui repellendus et. Ipsa doloribus architecto.","price":93901.86,"header":"Ex cumque qui odit.","footer":"Omnis explicabo est consectetur.","moreInfo":"Sed nostrum a qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
