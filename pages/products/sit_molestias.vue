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
      return {"slug":"sit_molestias","name":"Ipsa molestiae esse quod.","description":"Voluptatem vero aut. Quia officiis alias. Est at sit.","price":95310.88,"header":"Voluptatum nihil necessitatibus cupiditate.","footer":"Dignissimos assumenda voluptas omnis.","moreInfo":"Sunt sunt amet hic."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
