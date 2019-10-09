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
      return {"slug":"consequatur_asperiores","name":"Commodi hic facere omnis.","description":"Inventore et est. Ipsa aut quia. Praesentium dignissimos sit.","price":21093.47,"header":"Id voluptatum illo repellendus.","footer":"Officiis harum ipsa ducimus.","moreInfo":"Numquam itaque quidem placeat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
