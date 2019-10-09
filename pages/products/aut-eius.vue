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
      return {"slug":"aut-eius","name":"Eum numquam repellat sapiente.","description":"Autem ducimus corrupti. Molestiae qui voluptatem. Et ipsum occaecati.","price":15599.03,"header":"Fugit culpa aut voluptatem.","footer":"Est veniam quia voluptate.","moreInfo":"Repellendus doloribus aut cumque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
