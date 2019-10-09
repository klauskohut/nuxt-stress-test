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
      return {"slug":"eaque_necessitatibus","name":"Sapiente modi ipsum incidunt.","description":"Commodi fugiat deserunt. Suscipit quae in. Omnis et minima.","price":91629.55,"header":"Et non est ipsam.","footer":"Sunt error voluptatem id.","moreInfo":"Occaecati adipisci voluptatem ullam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
